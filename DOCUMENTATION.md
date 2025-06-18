# WP Rocket Redis Cache Extension - Documentación Detallada

---

<details>
<summary>🇪🇸 Español</summary>

## Introducción

Este plugin extiende la funcionalidad del plugin WP Rocket para integrar **Redis** como sistema avanzado de caché. Su objetivo es mejorar el rendimiento del sitio web almacenando las páginas en memoria rápida (Redis), y gestionando la limpieza del caché de forma automática y eficiente.

## ¿Qué hace el plugin?

1. Extiende la clase Cache de WP Rocket para usar Redis en lugar del sistema de archivos.
2. Conecta a Redis en `localhost:6379` y usa un prefijo para evitar colisiones.
3. Sobrescribe métodos para guardar, leer y borrar caché en Redis.
4. Inicializa automáticamente si WP Rocket está activo.
5. Limpia automáticamente la caché al actualizar o borrar posts.
6. Añade acción administrativa para limpiar toda la caché Redis manualmente.

## Requisitos

- Servidor Redis corriendo en localhost puerto 6379.
- WP Rocket activo.
- PHP con extensión phpredis.

## Beneficios

- Mejora notable del rendimiento.
- Compatibilidad multisite.
- Limpieza automática para evitar caché obsoleta.

## Uso

1. Instala Redis.
2. Activa el plugin.
3. La caché se gestiona en Redis automáticamente.
4. Para limpiar toda la caché, usa el enlace `admin-post.php?action=clear_all_redis_cache`.

</details>

---

<details>
<summary>🇺🇸 English</summary>

## Introduction

This plugin extends WP Rocket functionality to integrate **Redis** as an advanced caching system. It improves site performance by storing pages in fast memory (Redis) and manages cache cleaning automatically and efficiently.

## What does the plugin do?

1. Extends WP Rocket's Cache class to use Redis instead of the file system.
2. Connects to Redis at `localhost:6379` using a prefix to avoid collisions.
3. Overrides methods to write, read, and delete cache in Redis.
4. Initializes automatically if WP Rocket is active.
5. Automatically clears cache when posts are updated or deleted.
6. Adds an admin action to manually clear all Redis cache.

## Requirements

- Redis server running on localhost port 6379.
- WP Rocket active.
- PHP with phpredis extension.

## Benefits

- Significant performance improvements.
- Multisite compatibility.
- Automatic cleaning to avoid stale cache.

## Usage

1. Install Redis.
2. Activate the plugin.
3. Cache is automatically managed in Redis.
4. To clear all cache, use the link `admin-post.php?action=clear_all_redis_cache`.

</details>

---

<details>
<summary>🇫🇷 Français</summary>

## Introduction

Ce plugin étend WP Rocket pour intégrer **Redis** comme système de cache avancé. Il améliore les performances du site en stockant les pages en mémoire rapide (Redis) et gère automatiquement le nettoyage du cache.

## Que fait le plugin ?

1. Étend la classe Cache de WP Rocket pour utiliser Redis au lieu du système de fichiers.
2. Se connecte à Redis sur `localhost:6379` avec un préfixe pour éviter les collisions.
3. Remplace les méthodes pour écrire, lire et supprimer le cache dans Redis.
4. S'initialise automatiquement si WP Rocket est actif.
5. Nettoie automatiquement le cache lors des mises à jour ou suppressions d'articles.
6. Ajoute une action admin pour vider manuellement tout le cache Redis.

## Prérequis

- Serveur Redis fonctionnant sur localhost port 6379.
- WP Rocket actif.
- PHP avec extension phpredis.

## Avantages

- Amélioration significative des performances.
- Compatibilité multisite.
- Nettoyage automatique pour éviter le cache obsolète.

## Utilisation

1. Installez Redis.
2. Activez le plugin.
3. Le cache est automatiquement géré dans Redis.
4. Pour vider tout le cache, utilisez le lien `admin-post.php?action=clear_all_redis_cache`.

</details>

---

<details>
<summary>🇵🇹 Português</summary>

## Introdução

Este plugin estende o WP Rocket para integrar **Redis** como sistema avançado de cache. Ele melhora o desempenho do site armazenando páginas em memória rápida (Redis) e gerencia a limpeza do cache automaticamente.

## O que o plugin faz?

1. Estende a classe Cache do WP Rocket para usar Redis em vez do sistema de arquivos.
2. Conecta ao Redis em `localhost:6379` usando um prefixo para evitar colisões.
3. Sobrescreve métodos para gravar, ler e excluir cache no Redis.
4. Inicializa automaticamente se o WP Rocket estiver ativo.
5. Limpa automaticamente o cache ao atualizar ou excluir posts.
6. Adiciona ação administrativa para limpar todo o cache Redis manualmente.

## Requisitos

- Servidor Redis rodando em localhost porta 6379.
- WP Rocket ativo.
- PHP com extensão phpredis.

## Benefícios

- Melhora significativa no desempenho.
- Compatibilidade multisite.
- Limpeza automática para evitar cache desatualizado.

## Uso

1. Instale o Redis.
2. Ative o plugin.
3. O cache é gerenciado automaticamente no Redis.
4. Para limpar todo o cache, use o link `admin-post.php?action=clear_all_redis_cache`.

</details>

---

<details>
<summary>🇨🇳 简体中文</summary>

## 介绍

此插件扩展了 WP Rocket 功能，将 **Redis** 作为高级缓存系统集成。通过将页面存储在快速内存（Redis）中，提升网站性能，并自动高效地管理缓存清理。

## 插件功能

1. 扩展 WP Rocket 的 Cache 类，使用 Redis 替代文件系统。
2. 连接到 `localhost:6379` 的 Redis，使用前缀避免冲突。
3. 重写写入、读取和删除缓存的方法。
4. 如果 WP Rocket 激活，则自动初始化。
5. 在文章更新或删除时自动清理缓存。
6. 添加管理员操作，允许手动清理所有 Redis 缓存。

## 要求

- 运行在 localhost 6379 端口的 Redis 服务器。
- WP Rocket 已激活。
- PHP 已启用 phpredis 扩展。

## 优点

- 显著提升性能。
- 支持多站点。
- 自动清理，避免缓存过期。

## 使用方法

1. 安装 Redis。
2. 激活插件。
3. 缓存将自动管理于 Redis 中。
4. 要清理所有缓存，请访问链接 `admin-post.php?action=clear_all_redis_cache`。

</details>
