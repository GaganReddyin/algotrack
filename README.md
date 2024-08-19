# algotrack
Deployed at: https://algotrack.onrender.com/
# **Algotrack (Search Engine for Coding Problems)**

**Algotrack** is a search engine designed specifically for finding coding problems on LeetCode. It uses web scraping and the TF-IDF algorithm to help users locate relevant problems based on their search queries, making it easier to practice and improve coding skills.


## **Features**
- **Web Scraping:** Extracts coding problem data from multiple platforms using Beautiful Soup and Selenium.
- **Search Algorithm:** Implements the TF-IDF algorithm to rank and retrieve problems based on query relevance.
- **Interactive Web Interface:** Built with React.js and Node.js, offering a seamless and responsive user experience.
- **Cross-Platform Search:** Allows users to search and view coding problems across various platforms in a unified interface.

## **Tech Stack**
- **Frontend:** React.js, HTML, CSS
- **Backend:** Node.js, Python
- **Web Scraping:** Beautiful Soup, Selenium
- **Algorithm:** TF-IDF for search relevance

## **Setup Instructions**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GaganReddyin/Algotrack
2. **Navigate to the project directory and install dependencies:**
   ```bash
   cd Algotrack
   npm install
3. **Build the project to generate the build assets:**
   ```bash
   npm run build
4. **Start the application:**
   ```bash
   npm start

## **Usage**
1. **Perform a Search:**
   - Enter a search query (e.g., "dynamic programming") in the search bar.
   - Select the coding platform (LeetCode, Codeforces, CodeChef) to search from.

2. **View Results:**
   - The application displays a list of relevant coding problems with titles, links, and difficulty ratings.

## **Troubleshooting**
  - **Build Directory Issue:** If the `./build` directory does not exist, ensure that the build command (`npm run build`) was executed successfully and that the build directory is created.
- **Dependency Problems:** If there are issues with dependencies, try running `npm install` again to ensure all packages are correctly installed.
- **Deployment Issues:** Refer to the [Render Troubleshooting Guide](https://docs.render.com/troubleshooting-deploys) for more detailed support on deployment problems.

