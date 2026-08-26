# 🔎 e_LootSearch

> **Search the world. Find what others miss.**

A highly configurable **DayZ loot-search system** that allows players to investigate static environment objects such as refrigerators, lockers, dumpsters, and other configured props.

![(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpoLqb0msKGKKg6Dq9pOFap2DGxs769FRV6sAdB1ym3LGUDoQ2SP3wJBTm&s=10)](https://img.shields.io/badge/DayZ-Mod-blue)
![Bring your own!](https://img.shields.io/badge/Loot%20Tables-Configurable-green)
![Offline Tool](https://img.shields.io/badge/Config%20Generator-Offline-orange)

---

## ⚙️ FEATURES

| Feature                         | Description                                                                    |
| ------------------------------- | ------------------------------------------------------------------------------ |
| 🔎 **Interactive Searching**    | Search configured static environment props using your hands or specific tools. |
| 🎒 **Custom Loot Tables**       | Define exactly what each object can contain.                                   |
| ⚖️ **Weighted Drops**           | Control loot probabilities and drop weights.                                   |
| 📦 **Min / Max Amounts**        | Configure item quantity ranges for every loot entry.                           |
| 🧩 **Per-Object Configuration** | Give different props completely different loot pools.                          |
| 🛠️ **Visual Config Generator** | Edit your configuration through the included offline HTML tool.                |
| 📋 **Types.xml Autocomplete**   | Load your server's `types.xml` for faster item configuration.                  |

---

## 🚀 QUICK START

The server configuration is stored at:

```text
$profile:e_Mods/e_LootSearch.json
```

The easiest way to create and edit the configuration is:

```text
ConfigGenerator.html
```

The generator can parse your server's:

```text
types.xml
```

and use the available classnames for autocomplete.

> **Need to know which environment objects can be targeted?**
>
> Check `SERVER_PROPS_GUIDE.md` for the supported static props and target configuration.

---

## 🧰 CONFIGURATION

e_LootSearch lets you define:

* 🏷️ Target object types
* 🎒 Loot classnames
* 🔢 Minimum / maximum quantities
* ⚖️ Drop weights
* 🛠️ Required search tools
* 🔄 Custom loot pools

This allows completely different loot behavior for different environmental objects.

For example:

```text
Refrigerator
    ├── Food
    ├── Drinks
    └── Kitchen Items

Locker
    ├── Clothing
    ├── Tools
    └── Equipment

Dumpster
    ├── Junk
    ├── Scrap
    └── Random Items
```

---

# 🌍 LANGUAGES

* 🇬🇧 [English](#en-elootsearch)
* 🇪🇸 [Español](#es-elootsearch)
* 🇵🇹 [Português](#pt-elootsearch)
* 🇫🇷 [Français](#fr-elootsearch)
* 🇩🇪 [Deutsch](#de-elootsearch)
* 🇮🇹 [Italiano](#it-elootsearch)
* 🇵🇱 [Polski](#pl-elootsearch)
* 🇨🇿 [Čeština](#cs-elootsearch)
* 🇷🇺 [Русский](#ru-elootsearch)
* 🇨🇳 [简体中文](#zh-cn-elootsearch)
* 🇹🇼 [繁體中文](#zh-tw-elootsearch)
* 🇯🇵 [日本語](#ja-elootsearch)

---

# 🇬🇧 EN · e_LootSearch

### SEARCH THE ENVIRONMENT

A highly configurable DayZ mod that allows players to search static objects such as refrigerators, lockers, garbage bins, and other configured environmental props.

### ✦ FEATURES

**🔎 Interactive Searching**
Search static environment props using your hands or specific tools.

**🎒 Custom Loot Tables**
Define exactly which items can appear in each object type.

**⚖️ Weighted Drops**
Control the probability of individual loot entries.

**🔢 Min / Max Amounts**
Define quantity ranges for generated items.

**🛠️ Visual Config Generator**
Use the included offline `ConfigGenerator.html` to create and edit your configuration.

**📋 Types.xml Autocomplete**
Load your server's `types.xml` to automatically populate item classnames.

### 📁 CONFIGURATION

Configuration:

```text
$profile:e_Mods/e_LootSearch.json
```

Tools:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Use `ConfigGenerator.html` to edit the configuration visually.

See `SERVER_PROPS_GUIDE.md` for valid searchable targets.

---

# 🇪🇸 ES · e_LootSearch

### EXPLORÁ EL ENTORNO

Un mod altamente configurable para DayZ que permite a los jugadores buscar loot en objetos estáticos como heladeras, casilleros, contenedores de basura y otros props configurados.

### ✦ CARACTERÍSTICAS

**🔎 Búsqueda Interactiva**
Los jugadores pueden registrar objetos estáticos utilizando las manos o herramientas específicas.

**🎒 Tablas de Loot Personalizadas**
Definí exactamente qué objetos pueden aparecer en cada tipo de prop.

**⚖️ Drops por Peso**
Controlá la probabilidad relativa de cada objeto.

**🔢 Cantidades Mínimas y Máximas**
Configurá el rango de cantidad generado para cada item.

**🛠️ Generador Visual**
Editá la configuración mediante `ConfigGenerator.html`, incluido como herramienta offline.

**📋 Autocompletado desde types.xml**
Cargá el `types.xml` de tu servidor para utilizar los classnames automáticamente.

### 📁 CONFIGURACIÓN

La configuración se guarda en:

```text
$profile:e_Mods/e_LootSearch.json
```

Herramientas:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Usá `ConfigGenerator.html` para editar la configuración visualmente.

Consultá `SERVER_PROPS_GUIDE.md` para conocer los targets válidos.

---

# 🇵🇹 PT · e_LootSearch

### VASCOULHE O AMBIENTE

Um mod altamente configurável para DayZ que permite aos jogadores procurar loot em objetos estáticos, como frigoríficos, armários, lixeiras e outros objetos configurados.

### ✦ RECURSOS

**🔎 Busca Interativa**
Procure objetos estáticos usando as mãos ou ferramentas específicas.

**🎒 Tabelas de Loot Personalizadas**
Defina exatamente quais itens podem aparecer em cada tipo de objeto.

**⚖️ Drops por Peso**
Controle a probabilidade relativa de cada item.

**🔢 Quantidades Mínimas e Máximas**
Configure os limites de quantidade para cada item.

**🛠️ Gerador Visual**
Edite a configuração usando o `ConfigGenerator.html` offline.

**📋 Autocomplete via types.xml**
Carregue o `types.xml` do seu servidor para preencher automaticamente os classnames.

### 📁 CONFIGURAÇÃO

```text
$profile:e_Mods/e_LootSearch.json
```

Ferramentas:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Consulte `SERVER_PROPS_GUIDE.md` para os targets válidos.

---

# 🇫🇷 FR · e_LootSearch

### FOUILLEZ L'ENVIRONNEMENT

Un mod DayZ hautement configurable permettant aux joueurs de fouiller des objets statiques tels que les réfrigérateurs, casiers, poubelles et autres objets configurés.

### ✦ FONCTIONNALITÉS

**🔎 Fouille interactive**
Fouillez les objets avec vos mains ou des outils spécifiques.

**🎒 Tables de loot personnalisées**
Définissez précisément les objets pouvant apparaître dans chaque type de contenant.

**⚖️ Drops pondérés**
Contrôlez les probabilités relatives de chaque objet.

**🔢 Quantités min / max**
Définissez les quantités minimales et maximales.

**🛠️ Générateur visuel**
Utilisez `ConfigGenerator.html` pour modifier la configuration hors ligne.

**📋 Autocomplétion types.xml**
Chargez le `types.xml` de votre serveur pour obtenir les classnames automatiquement.

### 📁 CONFIGURATION

```text
$profile:e_Mods/e_LootSearch.json
```

Outils :

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Consultez `SERVER_PROPS_GUIDE.md` pour les targets valides.

---

# 🇩🇪 DE · e_LootSearch

### DIE UMGEBUNG DURCHSUCHEN

Eine hochgradig konfigurierbare DayZ-Mod, mit der Spieler statische Objekte wie Kühlschränke, Spinde, Mülltonnen und andere konfigurierte Objekte durchsuchen können.

### ✦ FUNKTIONEN

**🔎 Interaktive Suche**
Durchsuche Objekte mit den Händen oder bestimmten Werkzeugen.

**🎒 Eigene Loot-Tabellen**
Definiere genau, welche Items in jedem Objekttyp erscheinen können.

**⚖️ Gewichtete Drops**
Steuere die relative Wahrscheinlichkeit jedes Items.

**🔢 Min / Max Mengen**
Definiere minimale und maximale Itemmengen.

**🛠️ Visueller Config-Generator**
Bearbeite deine Konfiguration offline mit `ConfigGenerator.html`.

**📋 types.xml Autovervollständigung**
Lade deine Server-`types.xml`, um Classnames automatisch zu verwenden.

### 📁 KONFIGURATION

```text
$profile:e_Mods/e_LootSearch.json
```

Tools:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Siehe `SERVER_PROPS_GUIDE.md` für gültige Targets.

---

# 🇮🇹 IT · e_LootSearch

### CERCA NELL'AMBIENTE

Un mod DayZ altamente configurabile che permette ai giocatori di cercare loot all'interno di oggetti statici come frigoriferi, armadietti, bidoni della spazzatura e altri oggetti configurati.

### ✦ FUNZIONALITÀ

**🔎 Ricerca Interattiva**
Cerca negli oggetti utilizzando le mani o strumenti specifici.

**🎒 Tabelle Loot Personalizzate**
Definisci esattamente quali oggetti possono apparire in ogni contenitore.

**⚖️ Drop Pesati**
Controlla la probabilità relativa di ogni oggetto.

**🔢 Quantità Min / Max**
Imposta i limiti di quantità per ogni item.

**🛠️ Generatore Visuale**
Modifica la configurazione offline tramite `ConfigGenerator.html`.

**📋 Autocompletamento types.xml**
Carica il `types.xml` del server per ottenere automaticamente i classnames.

### 📁 CONFIGURAZIONE

```text
$profile:e_Mods/e_LootSearch.json
```

Strumenti:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Consulta `SERVER_PROPS_GUIDE.md` per i target validi.

---

# 🇵🇱 PL · e_LootSearch

### PRZESZUKUJ ŚWIAT

Wysoce konfigurowalny mod DayZ pozwalający graczom przeszukiwać statyczne obiekty, takie jak lodówki, szafki, śmietniki i inne skonfigurowane obiekty.

### ✦ FUNKCJE

**🔎 Interaktywne wyszukiwanie**
Przeszukuj obiekty rękami lub określonymi narzędziami.

**🎒 Własne tabele łupów**
Dokładnie określ, jakie przedmioty mogą pojawić się w danym obiekcie.

**⚖️ Wagi dropów**
Kontroluj względne prawdopodobieństwo każdego przedmiotu.

**🔢 Min / Max ilości**
Ustaw zakres ilości generowanych przedmiotów.

**🛠️ Wizualny generator konfiguracji**
Edytuj konfigurację offline za pomocą `ConfigGenerator.html`.

**📋 Autouzupełnianie z types.xml**
Wczytaj serwerowy `types.xml`, aby automatycznie korzystać z classname'ów.

### 📁 KONFIGURACJA

```text
$profile:e_Mods/e_LootSearch.json
```

Narzędzia:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Zobacz `SERVER_PROPS_GUIDE.md`, aby sprawdzić prawidłowe targety.

---

# 🇨🇿 CS · e_LootSearch

### PROHLEDÁVEJTE PROSTŘEDÍ

Vysoce konfigurovatelný DayZ mód umožňující hráčům prohledávat statické objekty, jako jsou lednice, skříňky, popelnice a další nakonfigurované objekty.

### ✦ FUNKCE

**🔎 Interaktivní hledání**
Prohledávejte objekty rukama nebo pomocí konkrétních nástrojů.

**🎒 Vlastní loot tabulky**
Určete, jaké předměty se mohou objevit v jednotlivých objektech.

**⚖️ Vážené dropy**
Nastavte relativní pravděpodobnost jednotlivých předmětů.

**🔢 Min / Max množství**
Nastavte minimální a maximální počet předmětů.

**🛠️ Vizuální generátor konfigurace**
Upravujte konfiguraci offline pomocí `ConfigGenerator.html`.

**📋 Automatické doplňování z types.xml**
Načtěte serverový `types.xml` pro automatické doplňování classname.

### 📁 KONFIGURACE

```text
$profile:e_Mods/e_LootSearch.json
```

Nástroje:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Platné targety najdete v `SERVER_PROPS_GUIDE.md`.

---

# 🇷🇺 RU · e_LootSearch

### ИССЛЕДУЙТЕ ОКРУЖЕНИЕ

Настраиваемый мод DayZ, позволяющий игрокам обыскивать статические объекты, такие как холодильники, шкафчики, мусорные контейнеры и другие настроенные объекты.

### ✦ ВОЗМОЖНОСТИ

**🔎 Интерактивный поиск**
Обыскивайте объекты руками или специальными инструментами.

**🎒 Пользовательские таблицы лута**
Точно определяйте, какие предметы могут появляться в каждом типе объекта.

**⚖️ Взвешенные шансы**
Настраивайте относительную вероятность выпадения предметов.

**🔢 Минимальное / максимальное количество**
Определяйте диапазон количества каждого предмета.

**🛠️ Визуальный генератор конфигурации**
Редактируйте конфигурацию через автономный `ConfigGenerator.html`.

**📋 Автодополнение из types.xml**
Загрузите серверный `types.xml` для автоматического заполнения classname.

### 📁 КОНФИГУРАЦИЯ

```text
$profile:e_Mods/e_LootSearch.json
```

Инструменты:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

Допустимые targets указаны в `SERVER_PROPS_GUIDE.md`.

---

# 🇨🇳 ZH-CN · e_LootSearch

### 搜索环境中的隐藏战利品

一个高度可配置的 DayZ 模组，允许玩家搜索冰箱、储物柜、垃圾桶以及其他已配置的静态环境对象。

### ✦ 主要功能

**🔎 互动搜索**
使用双手或指定工具搜索静态环境对象。

**🎒 自定义战利品表**
精确定义每种对象可以生成哪些物品。

**⚖️ 权重掉落**
控制每个物品的相对掉落概率。

**🔢 最小 / 最大数量**
设置每个物品生成数量的范围。

**🛠️ 可视化配置生成器**
使用离线 `ConfigGenerator.html` 编辑配置。

**📋 types.xml 自动补全**
加载服务器的 `types.xml` 自动获取 classname。

### 📁 配置

```text
$profile:e_Mods/e_LootSearch.json
```

工具：

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

有效目标请参考 `SERVER_PROPS_GUIDE.md`。

---

# 🇹🇼 ZH-TW · e_LootSearch

### 搜尋環境中的隱藏戰利品

一個高度可配置的 DayZ 模組，允許玩家搜尋冰箱、儲物櫃、垃圾桶以及其他已配置的靜態環境物件。

### ✦ 主要功能

**🔎 互動搜尋**
使用雙手或指定工具搜尋靜態環境物件。

**🎒 自訂戰利品表**
精確定義每種物件可以生成哪些物品。

**⚖️ 權重掉落**
控制每個物品的相對掉落機率。

**🔢 最小 / 最大數量**
設定每個物品生成數量的範圍。

**🛠️ 視覺化配置產生器**
使用離線 `ConfigGenerator.html` 編輯配置。

**📋 types.xml 自動補全**
載入伺服器的 `types.xml` 自動取得 classname。

### 📁 配置

```text
$profile:e_Mods/e_LootSearch.json
```

工具：

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

有效 targets 請參考 `SERVER_PROPS_GUIDE.md`。

---

# 🇯🇵 JA · e_LootSearch

### 環境を探索する

冷蔵庫、ロッカー、ゴミ箱などの静的オブジェクトを検索してアイテムを発見できる、高度に設定可能なDayZ modです。

### ✦ FEATURES

**🔎 インタラクティブ検索**
手や指定されたツールを使用して静的オブジェクトを検索できます。

**🎒 カスタムルートテーブル**
各オブジェクトに出現するアイテムを細かく設定できます。

**⚖️ ドロップウェイト**
各アイテムの相対的な出現確率を設定できます。

**🔢 最小 / 最大数量**
生成されるアイテム数量の範囲を設定できます。

**🛠️ ビジュアル設定ジェネレーター**
オフラインの `ConfigGenerator.html` を使用して設定を編集できます。

**📋 types.xml オートコンプリート**
サーバーの `types.xml` を読み込み、classname を自動補完できます。

### 📁 CONFIGURATION

```text
$profile:e_Mods/e_LootSearch.json
```

Tools:

```text
ConfigGenerator.html
SERVER_PROPS_GUIDE.md
```

有効な targets については `SERVER_PROPS_GUIDE.md` を参照してください。

---

## 📦 INCLUDED TOOLS

| File                    | Purpose                        |
| ----------------------- | ------------------------------ |
| `ConfigGenerator.html`  | Visual configuration editor    |
| `SERVER_PROPS_GUIDE.md` | Supported searchable objects   |
| `types.xml`             | Server loot classname source   |
| `e_LootSearch.json`     | Generated server configuration |

---

## 🧭 DOCUMENTATION MAP

```text
e_LootSearch
│
├── 🔎 Interactive Search
│
├── 🎒 Custom Loot Tables
│
├── ⚖️ Weighted Drops
│
├── 🛠️ ConfigGenerator.html
│
├── 📋 types.xml Autocomplete
│
└── 📖 SERVER_PROPS_GUIDE.md
```

---

### 📌 CONFIG PATH

```text
$profile:e_Mods/e_LootSearch.json
```

**Configure it. Search it. Loot it.**
