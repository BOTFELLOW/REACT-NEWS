# REACT-NEWS
## React News App

**A news aggregator built with React and the GNews API**

This project showcases a simple news application that fetches and displays news articles from various sources using the GNews API. It provides a user-friendly interface to explore news headlines and read detailed articles.

**Key Features:**

- **News Fetching:** Utilizes the GNews API to retrieve news articles based on different categories (business, entertainment, general, health, science, sports, technology).
- **Article Display:** Presents news articles with headlines, descriptions, images, and links to the original sources.
- **Search Functionality:** Allows users to search for specific news articles by keywords.
- **Responsive Design:** Ensures a seamless user experience across different devices and screen sizes.

**Getting Started:**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/react-news-app.git
   ```

2. **Install Dependencies:**

   ```bash
   cd react-news-app
   npm install
   ```

3. **Get a GNews API Key:**
   - Create a free account on the GNews API website: [https://gnews.io/](https://gnews.io/)
   - Obtain your API key.

4. **Set Up Environment Variables:**
   - Create a `.env` file in the project root directory.
   - Add your GNews API key:

     ```
     REACT_APP_GNEWS_API_KEY=your_api_key
     ```

5. **Start the Development Server:**

   ```bash
   npm start
   ```

6. **Access the App:**
   - Open your web browser and navigate to `http://localhost:3000`.

**Project Structure:**

- `src/`: Contains the main source code files.
- `public/`: Stores static assets like favicons and manifest files.
- `package.json`: Defines project dependencies and scripts.
- `.gitignore`: Specifies files and directories to exclude from version control.

**Contributing:**

Contributions are welcome! Feel free to submit pull requests or issues.

**License:**

This project is licensed under the MIT License.
