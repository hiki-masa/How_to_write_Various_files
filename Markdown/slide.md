---
marp: true
theme: default
header: "ヘッダータイトル"
footer: "フッタータイトル"

size: 16:9
paginate: true

style: |
    section.title {
        --title-height: 130px;
        --subtitle-height: 50px;

        overflow: visible;
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows:    1fr var(--title-height) var(--subtitle-height) 1fr;
        grid-template-areas:   "." "title" "subtitle" ".";
    }

    section.title h1 {
        --area-height: var(--title-height);

        margin:  0;
        padding: 0;
        text-align: center;
        height:      var(--area-height);
        line-height: var(--area-height);
        font-size: 40pt;
        grid-area: title;
    }

    section.title h2 {
        --area-height: var(--subtitle-height);

        margin:  0;
        padding: 0;
        text-align: center;
        height:      var(--area-height);
        line-height: var(--area-height);
        font-size: 30pt;
        grid-area: subtitle;
    }

    section {
        justify-content: start;
    }

    /* 数式 */
    section .formula {
        margin:  0;
        padding: 0;
        text-align: center;
        line-height: 100px;
        font-size: 30pt;
    }

    /* ページ総数を表示 */
    section::after {
        content: attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
    }

---

<!-- _class: title -->
<!-- _paginate: false -->
# タイトル
## サブタイトル

---

# 目次
- 目次1
- 目次2
- 目次3
