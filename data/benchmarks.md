# Benchmark Data — GenAI Video Models (February 2026)

## Structured Quality Benchmarks (1-10 Scale)

Test protocol: 50+ generations per model, identical prompt set of 15 categories (human motion, landscape, portrait, action, low-light, etc.), 4 seconds/720p/24fps, 2 independent reviewers, normalized to 0-10.

| Dimension | Kling 2.1 | Wan 2.2 | Veo 3 | Seedance 2.0 |
|-----------|-----------|---------|-------|-------------|
| Edge Stability | 5 | 6 | 7 | 8 |
| Motion Flow | 5 | 6 | 7 | 9 |
| Style Drift | 4 | 6 | 7 | 8 |
| Face Consistency | 4 | 5 | 7 | 7 |
| Camera Control | 4 | 5 | 7 | 9 |
| **Average** | **4.4** | **5.6** | **7.0** | **8.2** |

Source: Lanta AI Quantitative Benchmarks, 2026

## Seedance 2.0 Individual Output Ratings (Forest Tracking Shot)

| Metric | Score |
|--------|-------|
| Temporal Consistency | 9/10 |
| Camera Motion | 9/10 |
| Style Lock | 8/10 |
| Subject Stability | 8/10 |

## Community Elo Ratings (VBench / aifreeforever.com)

| Rank | Model | Elo Rating |
|------|-------|-----------|
| 1 | Runway Gen-4.5 | 1,247 |
| 2 | Veo 3 | 1,226 |
| 3 | Kling | 1,225 |
| 4 | Sora 2 | 1,206 |

Note: Elo captures user preference (aesthetic appeal); structured benchmarks capture technical quality. The gap between rankings suggests aesthetic factors beyond raw technical quality play a significant role in user perception.

## Temporal Consistency Summary

| Model | Temporal Consistency | Notes |
|-------|---------------------|-------|
| Seedance 2.0 | 9/10 (Leader) | "Environment Lock" — background objects remain stable over 15-20s |
| Sora 2 | Best-in-class | Best physics + temporal consistency combined |
| Veo 3.1 | Strong (broadcast-grade) | Strong color science, cinema-standard frame rate |
| Kling 3.0 | 6.8/10 (Weakest) | Struggles with multiple characters, fast movement blur |

*Last updated: 2026-02-14*
