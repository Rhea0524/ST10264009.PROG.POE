# Recipe Realm
### Cook with passion, dine with joy.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Configuration](#configuration)
6. [License](#license)
7. [Credits](#credits)
8. [Contact](#contact)
9. [Description of Changes](#description-of-changes)



## Introduction

Welcome to Recipe Realm, your ultimate companion for culinary exploration and recipe management! Recipe Realm is a versatile WPF application designed to streamline the process of organizing, scaling,experimenting with recipes and filtering recipes, all within a convenient command-line interface.

Whether you're a seasoned chef looking to fine-tune your favorite dishes or an aspiring home cook eager to explore new culinary horizons, Recipe Realm offers a user-friendly platform to bring your culinary visions to life.

Discover a world of possibilities with Recipe Realm:

- **Efficient Recipe Organization:** Easily input and organize your recipes with intuitive data management features.
- **Flexible Scaling Options:** Adjust serving sizes and ingredient quantities to suit any occasion or dietary preference.
- **Insightful Nutritional Information:** Stay informed about the calorie content and nutritional profile of your recipes, aiding in mindful meal planning.
- **Customizable Configuration:** Tailor Recipe Realm to your unique preferences and workflow with customizable settings and options.
- **Community Collaboration:** Join a vibrant community of culinary enthusiasts and share your recipes, tips, and experiences with like-minded individuals.
- **Filter Recipes:** Filter recipes based on the occasion and what your heart is looking for, be it by a specific ingridient, maxiumim number of calories or a certain food group.

Experience the joy of cooking like never before as you embark on a culinary journey filled with creativity, experimentation, and culinary delight. With Recipe Realm by your side, the possibilities are endless.

Dive into the world of Recipe Realm today and unlock the full potential of your culinary imagination!

## Features

Recipe Management:
Enter and organize recipes with details such as name, ingredients, and steps.

Display Recipe Details:
View the details of saved recipes, including ingredient quantities, calorie content, and cooking steps.

Scale Recipe:
Adjust the serving size of recipes to accommodate different occasions or preferences.

Reset Quantities:
Reset recipe quantities to their original values after scaling.

Food Group Information:
Access information about different food groups to understand their nutritional value and role in a balanced diet.

Calorie Information:
Learn more about calories, including their importance, ranges, and factors influencing caloric needs.

Calorie Exceed:
When a user inputs a recipe that exceeds 300 calories, the user is notifed of that.

Filtering:
A user is able to filter recipes based on their perference, the user can filter by either a specific ingridient, food group or maximum calories.

## Installation

To use Recipe Realm, follow these steps:

- Clone this repository to your local machine : [Link to GitHub Repository](https://github.com/VCDN-2024/prog6221-part-2-Rhea0524.git)
- Navigate to the directory containing the cloned repository.
- Compile the source code using a C# compiler.
- Click on the run button once the code has opened.
- The code will now run and user will be able to use Recipe Realm

## Usage

Once installed, you can use Recipe Realm for the following tasks:

- **Enter Recipe Details:** Input the name, ingredients, and steps of your recipes.
- **Display Recipe:** View the details of saved recipes, including ingredient quantities, calorie content, and cooking steps.
- **Scale Recipe:** Adjust the serving size of recipes to accommodate different occasions or preferences.
- **Reset Quantities:** Reset recipe quantities to their original values after scaling.
- **Filtering Recipes:** Filter recipes based on user perference.

## Configuration

Recipe Realm does not require any specific configuration. However, users can customize the source code to add additional features or modify existing functionality as needed.

## License
Recipe Realm is licensed under the [MIT License](https://github.com/VCDN-2024/prog6221-part-2-Rhea0524/blob/main/MIT%20License). See the LICENSE file for details.

## Credits

Recipe Realm acknowledges the following contributions:

- [Microsoft C# Delegates Guide](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/delegates/)
- [Microsoft .NET List<T> Documentation](https://learn.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1?view=net-8.0)
- [Tutorialsteacher - C# Collections](https://www.tutorialsteacher.com/csharp/csharp-collection)
- [Understanding Food Groups](https://sweetlife.org.za/what-are-the-different-food-groups-a-simple-explanation/)
- [Understanding Calories](https://www.medicalnewstoday.com/articles/263028#:~:text=A%20calorie%20is%20a%20unit,reducing%20the%20intake%20of%20calories.)
- [How should I display in a view all the ingredients in/from a recipe when I am using WPF?](https://stackoverflow.com/questions/56432683/how-should-i-display-in-a-view-all-the-ingredients-in-from-a-recipe-when-i-am-us)
- [How do I display user input captured from a list in C#?](https://stackoverflow.com/questions/76301825/how-do-i-display-user-input-captured-from-a-list-in-c-sharp)
- [Display related data in WPF applications](https://learn.microsoft.com/en-us/visualstudio/data-tools/display-related-data-in-wpf-applications?view=vs-2022)
- [Persist and restore application-scope properties in WPF](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/app-development/persist-and-restore-application-scope-properties?view=netframeworkdesktop-4.8)
- [How to: Filter Data in a View (WPF)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/data/how-to-filter-data-in-a-view?view=netframeworkdesktop-4.8)
- [How to clear values in a DataGrid in C# WPF?](https://www.reddit.com/r/learnprogramming/comments/5gz5ne/how_to_clear_values_in_a_datagrid_in_c_wpf/)


## Contact

For questions or feedback, contact the Recipe Realm at **St10264009@vcconnect.edu.za**.

## Description of changes 

The feedback from my lecturer regarding Part 2 of the project is as follows:

**App Functionality:**
1. User Input and Explanation: The application allows users to enter the calories and food group for each ingredient. It is recommended to provide an explanation to users regarding the significance of these values.
2. Total Calories Calculation and Specific Explanation: The application calculates and displays the total calories of a recipe. It is advised to include a detailed explanation that pertains to specific calorie ranges.
3. Calorie Alert and Relevant Information: The application alerts the user when the total calories of a recipe exceed 300. It is essential to display information relevant to the calorie count as part of this alert.

**Application Structure:**
1. 300-Calorie Notification via Delegate: The 300-calorie notification should be implemented using a delegate. It is necessary to ensure the proper utilization of a delegate for this functionality.

**Implementation in Response to Feedback:**

**App Functionality:**
1. User Guidance: On the "Enter Recipe Details" page, I have added sticky notes that provide more information about the significance of the calorie and food group values. There are two sticky notes to guide the user appropriately.
2. Calorie Range Explanation: When a recipe is displayed, the total calories are calculated. I have included a brief explanation below this total to inform the user about what the specific calorie range of the recipe indicates.
3. Enhanced Calorie Alert: If a user inputs more than 300 calories on the "Enter Recipe Details" window, the warning now includes additional information related to the 300-calorie threshold.

**Application Structure:**
1. Delegate for Calorie Notification: I have implemented a delegate to ensure users are notified when a recipe exceeds 300 calories.



