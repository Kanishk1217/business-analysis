# Business Analyzer

A browser-based business intelligence platform. Upload any business CSV and instantly get KPI tracking, revenue forecasting, customer segmentation, ML predictions, and AI-generated insights — no data science knowledge required.

**Live demo:** https://business-analysis-3h9.pages.dev/

## What it does

| Feature | Description |
|---------|-------------|
| KPI Tracking | Period-over-period growth for every business metric in your CSV |
| Revenue Forecasting | Time-series model with confidence intervals and fitted vs actual view |
| Customer Segmentation | K-Means clustering with plain-English segment profiles |
| Correlation Analysis | Feature-to-feature heatmap, top correlated pairs surfaced automatically |
| ML Predictions | Auto classification or regression, scored Weak to Excellent |
| AI Business Story | Narrative insights synthesising all analysis into actionable recommendations |
| PDF Export | Full report download with all charts, tables, and insights |

## Stack

| Layer | Technology |
|-------|------------|
| Frontend | React + Vite + TypeScript |
| Styling | Tailwind CSS — dark glassmorphic theme |
| Charts | Recharts |
| PDF | jsPDF |
| Backend | Python + FastAPI |
| Hosting | Cloudflare Pages |

## Project structure

```
business-analysis/
├── frontend/    # React + Vite + TypeScript SPA
└── backend/     # Python FastAPI — ML, forecasting, segmentation, AI insights
```

## Running locally

**Frontend**
```bash
cd frontend
npm install
npm run dev
```

**Backend**
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

## Related

- [CSV Analyzer](https://github.com/Kanishk1217/csv-analysis) — the general-purpose foundation this project extends
