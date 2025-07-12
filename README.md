# 💰 Expense Tracker App  
📺 **YouTube Demo**: [https://youtube.com/shorts/bj0u58oK8ds](https://www.youtube.com/watch?v=c9j_gt3IjJI)

![App Screenshot](./expensetracker.png)

This repo contains a fully‑featured Flutter expense tracker:

- ✅ Riverpod for state
- ✅ Hive for storage
- ✅ GoRouter for navigation
- ✅ fl_chart for 3 distinct visualizations
- ✅ Professional UI/UX with empty states
- ✅ Git workflow with protected main + feature branches

## Running

```bash
flutter pub get
flutter run
```

## Code Generation (Hive)

```bash
dart run build_runner build --delete-conflicting-outputs
```

## Branching Scheme (suggested)

```text
main
├── feat/hive-setup-and-model
├── feat/router-setup
├── feat/riverpod-expense-provider
├── feat/expense-list-screen
├── feat/expense-crud-ui
└── feat/expense-graphs
```
Each feature branch is merged into **main** via Pull Requests, which you review yourself (simulating a team environment). The **main** branch is protected.
