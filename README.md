# ff_shoprobbery
A highly optimized store robbery system, with animations, props and networked scenes, with framework support for ESX, QB, Qbox & Mythic.

# Documenation
https://fiveforge-studios.gitbook.io/docs/free-resources/store-robbery

# Features
* **Target** - Supports (ox_target, qb-target, qtarget & mythic-targeting)
* **Syncing** - Uses entity & global statebags to handle syncing data between all clients with ease.
* **Dispatch** - Supports all common used dispatches (cd_dispatch, qs-dispatch, ps-dispatch, rcore_dispatch, mythic-mdt)
* **Commands** - Police can reset individual or all stores at once with /resetstore store_id and /resetstores
* **Scenes** - Uses networked scenes for props and interactivity.

# Performance
* **Optimization** - Server and client code runs at 0.01ms, with a short jump up to 0.05ms when you’re near the bag of money pickup, until somebody picks it up.
* **Secure** - Consistent and validation checks.
