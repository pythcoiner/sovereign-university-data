## Courses structure
```
── btc101
│   ├── assets
│   │   ├── artboard_1.png
│   │   ├── formation_1_final.png
│   │   ├── Concept
│   │   │   ├── chapitre0
│   │   │   │   ├── 0.jpeg
│   │   │   │   ├── 1.jpeg
│   │   │   ├── chapitre1
│   │   │   │   ├── 1.JPEG
│   │   │   ├── chapitre2
│   │   │   │   ├── 1.jpeg
│   │   │   │   ├── 2.jpeg
│   │   ├── posters
│   │   │   ├── en
│   │   │   │   ├── 10._set_up_your_wallet.png
│   │   │   │   ├── 11._explaination_of_a_transaction.png
│   │   │   ├── esp
│   │   │   │   ├── 10_configurar_tu_monedero.png
│   │   │   │   ├── 11_explicacion_de_una_transaccion.png
│   │   │   └── info.md
│   │   └── thumbnail.png
│   ├── course.yml
│   ├── de.md
│   ├── en.md
│   ├── es.md
│   ├── fr.md
│   ├── it.md
│   └── pt.md
── btc102
│   ├── assets
│   │   ├── artboard_1.png
│   │   ├── formation_1_final.png
│   │   ├── Concept
│   │   │   ├── chapitre0
│   │   │   │   ├── 0.jpeg
│   │   │   │   ├── 1.jpeg
│   │   │   ├── chapitre1
│   │   │   │   ├── 1.JPEG
│   │   │   ├── chapitre2
│   │   │   │   ├── 1.jpeg
│   │   │   │   ├── 2.jpeg
│   │   ├── posters
│   │   │   ├── en
│   │   │   │   ├── 10._set_up_your_wallet.png
│   │   │   │   ├── 11._explaination_of_a_transaction.png
│   │   │   ├── esp
│   │   │   │   ├── 10_configurar_tu_monedero.png
│   │   │   │   ├── 11_explicacion_de_una_transaccion.png
│   │   │   └── info.md
│   │   └── thumbnail.png
│   ├── course.yml
│   ├── de.md
│   ├── en.md
│   ├── es.md
│   ├── fr.md
│   ├── it.md
│   └── pt.md
```

## Structure of course.yml

```
level: <beginner | intermediate | expert>
hours: <estimated_hours>

professors:
  - <prof_1>
  - <prof_2>

contributors:
  - <contrib_1>
  - <contrib_2>
```

## Structure of <language>.md

```
---
name: <course_name>
goal: <goal_description>
objectives:
  - <objective_1>
  - <objective_2>
  - <objective_3>
---

# <description_name>

<course_description>

+++


# <section_0_name>

## <chapter_0_name>

<chapter_0>


# <section_1_name>

## <chapter_1_name>

<chapter_1>


# <section_2_name>


## <chapter_2_name>

<chapter_2>


## <chapter_3_name>

<chapter_3>


```
