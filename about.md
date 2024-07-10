---
layout: default
---

# This is H1
foobar
newline

## This is H2
{{ site.time }}
x-bookurl is {{ site.x-bookurl }}

<!-- <table><thead><tr><th><th>fasting<th>pp<th>bwt<th>onset<th>저혈당<tbody><tr><td>SU<td>2-<td>2-<td>+<td>즉시<td>유발가능<tr><td>Meglitinide<td>-<td>2-<td>+<td>즉시<td>유발가능<tr><td>Metformin<td>2-<td>-<td>0-<td>몇주<td><tr><td>Thiazolidinedione<td>2-<td>-<td>+<td>몇주<td><tr><td>α-glucosidase inhibitor<td>0<td>2-<td>0<td>즉시<td><tr><td>DPP-4i<td>-<td>2-<td>0<td>즉시<td><tr><td>GLP-1 RA<td>- 2-<td>2- 3-<td>-<td>즉시<td><tr><td>SGLT2i<td>2-<td>-<td>-<td>즉시<td><tr><td>basal insulin<td>2- 3-<td>0<td>+<td>즉시<td><tr><td>prandial insulin<td>0<td>2- 3-<td>+<td>즉시<td>

html표 -->

[a href link](qwer)

|     | fasting | pp  | bwt | onset |
| --- | ------- | --- | --- | ----- |
| SU  | 2-      | 2-  | +   | 즉시  |
| met | 2-      | -   | 0-  | 몇주  |
| SU  | 2-      | 2-  | +   | 즉시  |
| met | 2-      | -   | 0-  | 몇주  |
| SU  | 2-      | 2-  | +   | 즉시  |
| met | 2-      | -   | 0-  | 몇주  |

md표

## Diagram? ([GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams))
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```