# FastEat Recipe App

FastEat is a dynamic and responsive food recipe application built with React.js. The app fetches data from the MealDB API to display recipes based on various categories, details for specific meals, and more.

## Preview

Here is a preview of the FastEat Recipe App:

- ![Screenshot (22)](https://github.com/user-attachments/assets/f7ebc71e-1e7a-4f68-a79b-3eb459261686)

## Features

- **Home Page**: Displays all recipe categories.
- **Meal Details**: View detailed information about a selected meal.
- **Category View**: Explore recipes filtered by category.
- **Error Handling**: Custom error page for unmatched routes.
- **Responsive Layout**: Includes a header and a sidebar for easy navigation.

## Tech Stack

- **React.js**: For building the UI and managing component states.
- **React Router DOM**: For implementing routing.
- **SCSS**: For styling the application.

## Folder Structure

```
src
├── components
│   ├── Header
│   │   └── Header.js
│   ├── Sidebar
│       └── Sidebar.js
├── pages
│   ├── Home.js
│   ├── MealDetails.js
│   ├── Category.js
│   └── Error.js
├── App.js
├── App.scss
└── index.js
```



## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fast-eat-recipe-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fast-eat-recipe-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app will run at [http://localhost:3000](http://localhost:3000).

## Routes

- `/`: Displays the home page with recipe categories.
- `/meal/:id`: Shows details for a specific meal.
- `/meal/category/:name`: Displays all meals under a specific category.
- `*`: Displays a custom error page for unmatched routes.

## Components

- **Header**: The top navigation bar for the app.
- **Sidebar**: A sidebar for additional navigation options.

## Pages

1. **Home**: Main page displaying recipe categories.
2. **MealDetails**: Detailed information about a meal.
3. **Category**: Lists meals filtered by a specific category.
4. **Error**: A custom error page for invalid routes.

## API Integration

The app uses the [MealDB API](https://www.themealdb.com/api.php) to fetch recipe data dynamically.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
