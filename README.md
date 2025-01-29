## Project Title: Coins Table

### Description
"Coins Table" is a web app that helps users find the cheapest BTC prices from various providers. It uses **React** and **TypeScript** for development and **Tailwind CSS** for styling. The app fetches real-time data with **Axios** from an external API and displays it in a table.

**Key Features**:
- Debounced input to minimize API calls.
- Caching for faster load times.
- Loading skeletons to improve user experience.
- Responsive design with **Tailwind CSS**.

### Tools and Technologies Used:
- **React**: For building the UI.
- **TypeScript**: For type safety.
- **Tailwind CSS**: For styling.
- **Axios**: For making API requests.
- **Vite**: For fast development and build.
- **Aircode**: For backend API requests.

### Setup and Installation:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd coins-table
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and go to `http://localhost:3000`.

### File Structure:
- **src/App.tsx**: Main app component.
- **src/AmountInput.tsx**: Custom input component.
- **src/ResultRow.tsx**: Displays rows in the results table.
- **src/LoadingSkeleton.tsx**: Loading animation.
- **src/Input.tsx**: Manages input fields.
- **src/main.tsx**: Entry point for the app.
- **src/index.css**: Global styles and Tailwind CSS configuration.

