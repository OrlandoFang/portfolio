### About Me
I am currently pursuing an M.S. degree in Computer Science at Columbia University. I graduated from the University of Michigan - Ann Arbor with a Bachelor of Science in Computer Science. I am passionate about problem-solving, software development, UI/UX design, applications of artificial intelligence, and building innovative prediction models and data visualizations.

### Projects
#### [Brandforge AI: Multi-Agent Brand Generation Platform](EECS6895_Startup_AI_Agents_Platform-main.zip)
This is a multi-agent platform that transforms user descriptions into brand personas, logos, and marketing strategies, with support for asynchronous parallel generation. 
The frontend is built with the support of Figma Make and uses the React Framework. The backend is implemented in Python with the support of Cursor and Claude. It uses the FastAPI Framework and MongoDB for the database. The system architecture contains an AI gateway agent that assigns tasks to a Website agent that generates and renders HTML, a Logo agent with frontend skills that generates SVG and PNG logos, and a marketing agent that uses RAG to provide advertisement plans with platform recommendations and restrictions, as well as an AI-generated ad poster. The RAG utilizes two primary datasets: advertising performance benchmarks, including key metrics, such as CPC, CPM, CPA, CTR, and conversion rates, and a policy corpus that consists of platform-specific policy standards. Data were scraped from public sources. 
The AI pipeline contains structured brand-profile extraction, gateway-based parallel dispatch for multiple agents, RAG-based retrieval, template-driven planning, and compliance checks, integrated with OpenAI APIs. Reliability was improved through a standardized agent output contract and partial-failure tolerance, so single-agent errors do not break end-to-end generation. This is a team project based on one of my ideas for creating a creative AI agent. We worked on implementing the project together and cross-checked our work.

#### [Exploratory Data Analysis On Professional League of Legends Matches (Python)](https://orlandofang.github.io/most-exciting-league-in-league-of-legends/)
The project aims to analyze League of Legends Competitive Matches in 2022. Data obtained from Oracle’s Elixir. The dataset contains over 10,000 League of Legends competitive matches. The analysis will utilize the dataset and answer the following questions: Looking at tier-one professional leagues, which league has the most “action-packed” games? Is the amount of “action” in this league significantly different than in other leagues?
Steps include Data Cleaning, Exploratory Data Analysis, Assessment of Missingness, and Hypothesis Testing.

#### [Prediction Model On Professional League of Legends Matches (Python)](https://orlandofang.github.io/league-of-legends-role-prediction/)
I used the 2022 League of Legends Professional Matches dataset to create a prediction model that predicts the roles of individual players given their post-game data. In the project, I describe my process of improving my base model until I reached a final model with a 96.2% accuracy on unseen data. In the end, I also performed a Fairness Analysis.

#### [Data Visualizations on Factors Affecting Flight Delays (HTML, CSS, JS)](https://orlandofang.github.io/Flight_Delays/)
The project aims to analyze how various factors can affect the possibility of encountering flight delays in the US, and find the best airline, airport, and state for flights. I used common data visualizations so that the general audience, flight passengers, could understand my analysis without much knowledge of the topic. I also embedded data interactivity in three of the visualizations.
Note that this webpage can take around half a minute to load the visualizations because it processes more than 5 million rows of data.

### Contact
Feel free to reach out to me via:

Email: orlandofang0511@gmail.com
