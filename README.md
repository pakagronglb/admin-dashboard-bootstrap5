
# Admin Dashboard | Bootstrap 5

This project is a **responsive admin dashboard** built with **HTML**, **CSS**, **JavaScript**, and **Bootstrap 5**. It features a collapsible sidebar, a content area for managing data (such as tables and cards), and a responsive layout suitable for modern admin panels.

This project is based on the tutorial by **Codz Sword** (Dashboard Using Bootstrap 5 | Admin Template With Bootstrap 5 | Responsive Admin Dashboard Bootstrap)[https://www.youtube.com/watch?v=CzQhzULD5GA] 

## Features

- **Collapsible Sidebar**: The sidebar can expand and collapse on button click.
- **Responsive Design**: Built with Bootstrap 5 for responsiveness on various devices.
- **Dashboard Cards**: Displaying key data in card components with hover effects.
- **Data Tables**: A table layout for displaying information like user details or product data.
- **Navigation**: Sidebar navigation for switching between different sections of the admin dashboard.

## Technologies Used

- **HTML5**: For the markup and structure of the webpage.
- **CSS3**: Custom styles for layout and design.
- **Bootstrap 5**: For responsive layout and styling.
- **JavaScript**: Adds interactivity (e.g., sidebar toggle).
- **Google Fonts (Poppins)**: For modern typography.
- **Line Icons**: For a consistent and sleek iconography.

## Project Structure

```bash
├── index.html             # Main HTML file for the admin dashboard
├── style.css              # Custom CSS for styling the dashboard
├── script.js              # JavaScript for toggling sidebar functionality
└── assets/                # Optional folder for images, fonts, etc.
```

### index.html

- **Sidebar Navigation**: Contains links to different sections like Profile, Tasks, Auth, Multi-level menus, Notifications, and Settings.
- **Main Content Area**: Contains cards displaying important metrics and tables to manage or view data.
- **Footer**: Includes contact links and terms of service.

### style.css

- **Custom Styles**: Customizes Bootstrap's layout and styling, including hover effects, table styling, card design, and responsive adjustments.
- **Sidebar Styles**: Styles for the collapsible sidebar, including transitions for expanding and collapsing the sidebar.
- **Responsive Design**: Ensures the layout adapts well to different screen sizes, including mobile and tablet devices.

### script.js

- **Sidebar Toggle**: Handles the functionality of expanding and collapsing the sidebar when the hamburger menu icon is clicked.
- **Event Listener**: The JavaScript adds an event listener to toggle the `expand` class on the sidebar, which controls its visibility and width.

## Installation and Setup

1. **Download or Clone the Repository**:
   ```bash
   git clone https://github.com/pakagronglb/admin-dashboard-bootstrap5.git
   ```

2. **Open the Project**:
   Navigate to the project directory and open the `index.html` file in your browser.

   ```bash
   cd admin-dashboard-bootstrap5
   open index.html
   ```

3. **Customizing the Dashboard**:
   You can add more features or modify existing ones by editing the `index.html`, `style.css`, and `script.js` files to fit your needs.

## How to Use

- **Sidebar Navigation**: Click on the hamburger icon at the top-left corner to toggle the sidebar.
- **Dashboard Cards**: Hover over the cards to see the hover effect. These can display key performance indicators (KPIs) for the admin panel.
- **Data Table**: View user or product data in a tabular format. You can extend this with JavaScript or backend logic to dynamically populate data.
- **Footer Links**: Footer contains quick links such as Contact, About Us, and Terms & Conditions.

## Future Enhancements

- **Authentication Integration**: Add login and registration pages.
- **Dynamic Data Loading**: Use APIs to populate dashboard data (e.g., user stats, sales metrics).
- **Chart Integration**: Add charts for visual representation of data using libraries like **Chart.js**.

## License

This project is licensed under the MIT License.


---

This **README** provides a comprehensive overview of the **Admin Dashboard** project, detailing the technologies used, setup instructions, and how to customise and extend the dashboard.