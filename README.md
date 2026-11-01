# College Vegan Meal Planner

## Project Summary
A Java command-line program designed for college students to easily generate weekly vegan and plant based meal prep plans, based on available dorm/apartment kitchen equipment
(ex: microwave or mini-fridge only), as well as budget goals. The output will also include a grocery shopping list to save time and money.

## MVP (Minimum Viable Product)
- **Command Line Interface:** Prompts users for budget, current ingredients, and available equipment.
- **Recipe Database:** Based on the input, load vegan recipes from a local JSON file and filter them by prep time, protein content, and equipment needed.
- **Grocery List:** Combines and sums up ingredients needed across all generated recipes for the week into a single shopping list.
- **File Saving:** Saves generated meal plans and reads recipe data using local JSON files via the Gson library.

## Future Plans (V2.0+)
- Build a graphical user interface (GUI) / website / app
- Add a price estimator with the grocery list using local grocery store pricing APIs

## Tech Stack
- **Language:** Java 
- **Libraries:** Gson, java.util.Scanner, java.nio.file
- **Data Storage:** Local JSON files
  
## Relevant Docs
- [Eisenhower Matrix using draw.io platform](EisenhowerMatrixOliviaRutkowskiGoogleDocs.pdf)
- [System Diagram](flowchartOliviacs193.drawio.png)
