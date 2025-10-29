# 🧠 Laravel Database & ORM Master Roadmap (বাংলা গাইডলাইন)

এই গাইডে Laravel এর Database ও Eloquent ORM এর সবগুলো টপিক ধাপে ধাপে সাজানো আছে — বেসিক থেকে শুরু করে একদম অ্যাডভান্স লেভেল পর্যন্ত।

---

## 🔹 PART 1: Database Fundamentals (ডাটাবেজ মৌলিক ধারণা)

-   `.env` ফাইলে ডাটাবেজ কনফিগারেশন
-   `config/database.php` সেটআপ বোঝা
-   Raw SQL Query (`select`, `insert`, `update`, `delete`)
-   Binding (Named ও Positional)
-   Transaction (`beginTransaction`, `commit`, `rollback`)
-   Multiple Database Connections
-   Query Logging ও Debugging (`DB::listen`)

---

## 🔹 PART 2: Query Builder (বেসিক থেকে প্রো)

### 🧩 Basic

-   `select`, `where`, `orderBy`, `groupBy`, `limit`, `offset`
-   `pluck`, `value`, `first`, `count`, `sum`, `avg`, `max`, `min`

### 🧠 Intermediate

-   `join`, `leftJoin`, `crossJoin`
-   Conditional Query (`when`, `unless`)
-   Dynamic Where (`whereNameAndEmail`)
-   Pagination (`paginate`, `simplePaginate`)

### ⚡ Advanced

-   Raw Query (`DB::raw`, `selectRaw`, `whereRaw`)
-   JSON Query (`whereJsonContains`)
-   Chunking (`chunk`, `lazy`, `cursor`)
-   Query Macros
-   Query Performance Optimization

---

## 🔹 PART 3: Eloquent ORM (বেসিক থেকে অ্যাডভান্স)

-   Model তৈরি ও ব্যবহার (`make:model`)
-   `$fillable`, `$guarded`, `$hidden`, `$casts`
-   CRUD Operations (`create`, `find`, `update`, `delete`)
-   Query Scopes (Local ও Global)
-   Accessors ও Mutators
-   Timestamps ও Custom Primary Key
-   Soft Deletes
-   Model Events ও Observers
-   Factories ও Seeders
-   Eloquent Collection ও Chainable Query

---

## 🔹 PART 4: Eloquent Relationships (সম্পূর্ণ গাইড)

-   One To One
-   One To Many
-   Many To Many
-   HasOneThrough
-   HasManyThrough
-   Polymorphic (One To Many, Many To Many)
-   Custom Pivot Table (`withPivot`, `using`)
-   Relationship Query (`whereHas`, `doesntHave`, `withCount`)
-   Nested Relationship (`with('posts.comments')`)
-   Relationship Aggregate (`withSum`, `withAvg`)
-   Lazy Loading, Eager Loading, Lazy Eager Loading
-   Relationship Caching ও N+1 সমস্যা প্রতিরোধ

---

## 🔹 PART 5: Advanced Querying (জটিল কুয়েরি পরিচালনা)

-   Subquery Select ও Subquery Join
-   Raw Expression (`selectRaw`, `orderByRaw`)
-   Aggregates ও Reporting Query
-   Chunking ও Cursor Pagination
-   Repository Pattern ব্যবহার
-   Custom Eloquent Builder
-   Eager Load Constraints
-   Query Caching ও Profiling

---

## 🔹 PART 6: Migrations & Schema Builder

-   টেবিল তৈরি ও পরিবর্তন (`Schema::create`, `table`)
-   Column Types (string, integer, json, enum, ইত্যাদি)
-   Constraints (foreign, unique, index)
-   Table Modifiers (nullable, default, after, rename)
-   Transactional Migrations
-   Seeder ও Factory এর মাধ্যমে ডাটা তৈরি
-   Multiple Connection Migration
-   Schema Dump ও Optimization

---

## 🔹 PART 7: Performance & Optimization (দ্রুততা ও দক্ষতা)

-   Eager Loading দিয়ে N+1 সমস্যা সমাধান
-   `withCount`, `loadCount` ব্যবহার
-   Query Cache (Redis/File Cache)
-   Chunking ও Lazy Loading
-   Proper Index ব্যবহার
-   Telescope ও Debugbar দিয়ে Performance Track

---

## 🔹 PART 8: Advanced Concepts (অ্যাডভান্স কনসেপ্ট)

-   Multi Database Architecture
-   Custom Eloquent Casts
-   Query Encryption ও Decryption
-   Database Views এর সাথে কাজ করা
-   Repository + Service Layer Pattern
-   Data Transfer Objects (DTOs)
-   Model Resource & Resource Collection

---

## 🔹 PART 9: Database Advanced Tools

-   Database Transactions Deep Dive
-   Query Event Listener (`DB::listen`)
-   Query Caching ও Cache Invalidation
-   Big Data Handle (chunk, cursor, index)
-   Read/Write Connection Separation
-   View ও Materialized View ব্যবহার

---

## 🔹 PART 10: Hands-On Practice (প্র্যাকটিস প্রজেক্ট)

1. **Inventory Management System** – Complex joins, aggregates
2. **Multi-tenant CRM** – Tenant ভিত্তিক DB connection
3. **Blog System** – Polymorphic comments + tags
4. **Report Management** – Filtering, subquery, `withCount`
5. **E-commerce System** – Pivot Table, relationship, caching

---

## ✅ Master Checklist (স্ব-মূল্যায়ন)

| বিষয়                     | শিখেছো কিনা |
| ------------------------ | ----------- |
| Query Builder            | ☐           |
| ORM Basic                | ☐           |
| Relationship             | ☐           |
| Eager/Lazy Loading       | ☐           |
| Transactions             | ☐           |
| Performance Optimization | ☐           |
| Migration & Schema       | ☐           |
| Repository Pattern       | ☐           |
| Query Caching            | ☐           |
| Polymorphic Relations    | ☐           |
| Advanced Querying        | ☐           |

---

### 📘 লেখক

**রুপম ইহসান (Rupom Ehsan)**  
Full Stack Web Developer | Laravel, Vue.js, PHP  
GitHub: [rupomehsan](https://github.com/rupomehsan)
