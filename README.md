# Research Pipeline — Paper Digest + AI Podcast

Track arXiv papers by your own keywords, with AI-generated summaries and Chinese podcasts.

## User Guide

### 0. Customize Your Research Topics

Edit `config/topics.yaml` to control which papers the pipeline discovers. Add your own topics, keywords, and filters — no Python editing needed:

```yaml
topics:
  - name: "auto_scientific_discovery"
    display_name: "Auto Scientific Research"
    search_query: |
      cat:cs.AI AND ("autonomous scientific discovery" OR "AI scientist" \
        OR "scientific discovery agent" OR "automated research")
    max_results: 30
    abstract_contains: []
    any_keyword:
      - "scientific discovery"
      - "AI scientist"
      - "autonomous research"

  - name: "self_evolving_agent"
    display_name: "Self-Evolving Agents"
    search_query: |
      cat:cs.AI AND ("self-evolving" OR "self-improving" \
        OR "self-evolution") AND agent
    max_results: 25
    abstract_contains: []
    any_keyword:
      - "self-evolv"
      - "self-improv"
      - "self-evolution"

  - name: "llm_agent_science"
    display_name: "LLM Agents for Science"
    search_query: |
      cat:cs.AI AND (agent OR agentic) AND (science OR scientific \
        OR research) AND (LLM OR "language model")
    max_results: 30
    abstract_contains: []
    any_keyword:
      - "agent"
      - "scientific"
      - "research"

  - name: "ai_for_molecular_design"
    display_name: "AI for Molecular & Protein Design"
    search_query: |
      cat:cs.AI AND (protein OR molecule) AND (agent OR "language model") \
        AND (design OR optimization OR generation)
    max_results: 30
    abstract_contains: []
    any_keyword:
      - "protein"
      - "molecule"
      - "molecular"

  - name: "knowledge_evolution"
    display_name: "Knowledge Evolution & Code-as-Knowledge"
    search_query: |
      cat:cs.AI AND ("knowledge evolution" OR "knowledge base" \
        OR "skill library") AND (agent OR evolving)
    max_results: 20
    abstract_contains: []
    any_keyword:
      - "knowledge"
      - "skill"
```

**Configuration fields per topic:**
| Field | Description |
|-------|-------------|
| `name` | Internal identifier (snake_case) |
| `display_name` | Human-readable label shown on the website |
| `search_query` | arXiv API query (supports boolean ops, category filters like `cat:cs.RO`) |
| `max_results` | Papers to fetch per run (1–100, default 20) |
| `abstract_contains` | ALL keywords must appear in abstract (case-insensitive). Empty = disabled. |
| `any_keyword` | AT LEAST ONE keyword must appear in abstract (case-insensitive). Empty = disabled. |

### 1. Browse Papers

Visit the [GitHub Pages site](https://solitary2005.github.io/research_pipeline/) to browse daily arXiv papers. The system searches arXiv directly and updates each day at 12:00 UTC.

### 2. Request Summary + Podcast (arXiv papers)

On any paper's detail page, click **"Request Summary + Podcast"**. This opens a GitHub Issue — submit it and the workflow will:
- Download the PDF from arXiv
- Generate an English summary card
- Generate a Chinese podcast script (~15-30 min)
- Produce an MP3 audio file
- Add the paper to your Favorites

The result appears on the paper's podcast page within a few minutes.

### 3. Manually Upload a Paper

Have your own PDF? Use the **Manual Upload** feature:

1. Go to Issues → New Issue → **"Manual Paper Upload"**
2. Fill in the paper title, authors, and topic
3. **Drag and drop your PDF** into the form (or place it in `_uploads/` and reference its filename)
4. Submit the issue

The workflow automatically generates the summary card, podcast, and adds the paper to your Favorites — no separate "Request" step needed.

### 4. Listen to Podcasts

Each processed paper gets a dedicated podcast page with an embedded audio player. You can also browse all archived papers on the [Favorites page](https://solitary2005.github.io/research_pipeline/favorites/).

### 5. Remove from Favorites

On any favorited paper's page, click **"Remove from Favorites"**. This opens an issue — submit it to remove the paper from your collection (summary, podcast, and audio files will be cleaned up).

### 6. Cleanup

Papers that haven't been requested for summary/podcast are automatically removed after 7 days. Favorited papers are kept permanently.

---

<details>
<summary>📋 Setup & Configuration</summary>

### GitHub Secrets

| Secret | Required | Purpose |
|--------|----------|---------|
| `ANTHROPIC_API_KEY` | Optional | Claude API for summaries and podcasts |
| `OPENAI_API_KEY` | Optional | OpenAI GPT / TTS |
| `DEEPSEEK_API_KEY` | Yes (default) | DeepSeek as LLM backend |

### GitHub Pages

Enable Pages in repo Settings → Pages:
- Source: Deploy from a branch
- Branch: `main`, folder: `/ (root)`

### Topic Configuration

Paper discovery is controlled by `config/topics.yaml`. See [Section 0](#0-customize-your-research-topics) above for the full format. You can override the config path via the `TOPICS_CONFIG_PATH` environment variable.

### Backend Configuration

LLM and TTS backends are configured in `config/settings.yaml`:

```yaml
llm:
  backend: "deepseek"     # claude | openai | deepseek

tts:
  backend: "edge"         # edge | openai
```

Edit this file to switch backends — no need to touch workflow files. Environment variables (`LLM_BACKEND`, `TTS_BACKEND`) can still override these settings if needed.

You can override the config file path via environment variables:
- `SETTINGS_CONFIG_PATH` — path to `settings.yaml`
- `TOPICS_CONFIG_PATH` — path to `topics.yaml`

</details>

---

<details>
<summary>📝 Changelog</summary>

Full release notes are published on the [GitHub Releases](https://github.com/Solitary2005/research_pipeline/releases) page.

**Latest — Manual Paper Upload (2026-06-11)**
- New Issue template for manual PDF uploads (drag & drop)
- Uploaded papers go directly to Favorites + auto-generate summary card & podcast
- Supports non-arXiv papers with user-provided metadata
- Unmark workflow updated to support both arXiv IDs and manual paper IDs

[View all releases →](https://github.com/Solitary2005/research_pipeline/releases)

</details>
