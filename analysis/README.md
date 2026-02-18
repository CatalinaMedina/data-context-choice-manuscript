# Thematic analysis

*Below are the details of our thematic analysis for data context preference.*
*The thematic analysis for opinion on having choice of data context was conducted similarly.*

The thematic analysis for data context preference was an iterative process.
First we independently identify themes present in student responses. 
Each of us ran `data/02-data-wrangling.qmd` to produce the `data/cleaned-data/hw-context-reasons-themes-[name].csv` to record the themes for each response.
We then resolved any conflict to 

Intervention homework with choice had two questions, which we analyzed jointly:

1. Please explain in detail what led you to choose this topic, [topic], to investigate.
2. What was it about the other two options ([topic] and [topic]) that led you not to choose them? Please explain in detail.

The intervention homework with no choice had one question:

3. Please explain in detail what you liked and/or what you did not like about this data topic.

The themes are in `analysis/data-context-themes.csv`. 

Codebook guidelines:

- Separate multiple-coded themes with "; "
- Add "(converse)" to the end of a theme to mean the opposite of the theme's definition. 
Ex: If student 24 chose "ds_context1" because it would be easy to understand `ds_context1_theme = difficulty`. 
If student 25 did not choose `ds_context2` because it would be difficult to understand `ds_context2_theme = difficulty (converse)`.
- Enter no info into a column instead of leaving it NA when there is no theme to be identified (except the ..._reason columns can be left NA)