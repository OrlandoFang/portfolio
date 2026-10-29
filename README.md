### About Me
I am currently pursuing an M.S. degree in Computer Science at Columbia University. I graduated from the University of Michigan - Ann Arbor with a Bachelor of Science in Computer Science. I am passionate about AI engineering, software development, UI/UX design, product managing, and I am good at problem solving, communication, and challenging myself.

I am actively looking for New Grad roles in SWE, FDE, and AI PM. 

Feel free to reach out to me via: orlandofang0511@gmail.com

### Projects
#### [Brandforge AI: Multi-Agent Brand Generation Platform](https://orlandofang.github.io/BrandForge_AI--Multi-Agent_Brand_Generation_Platform/)
This is a multi-agent platform that transforms user descriptions into brand personas, logos, and marketing strategies, with support for asynchronous parallel generation. 
The frontend is built with the support of Figma Make and uses the React Framework. The backend is implemented in Python with the support of Cursor and Claude. It uses the FastAPI Framework and MongoDB for the database. The system architecture contains an AI gateway agent that assigns tasks to a Website agent that generates and renders HTML, a Logo agent with frontend skills that generates SVG and PNG logos, and a marketing agent that uses RAG to provide advertisement plans with platform recommendations and restrictions, as well as an AI-generated ad poster. The RAG utilizes two primary datasets: advertising performance benchmarks, including key metrics, such as CPC, CPM, CPA, CTR, and conversion rates, and a policy corpus that consists of platform-specific policy standards. Data were scraped from public sources. 

The AI pipeline contains structured brand-profile extraction, gateway-based parallel dispatch for multiple agents, RAG-based retrieval, template-driven planning, and compliance checks, integrated with OpenAI APIs. Reliability was improved through a standardized agent output contract and partial-failure tolerance, so single-agent errors do not break end-to-end generation. This is a team project based on one of my ideas for creating a creative AI agent. We worked on implementing the project together and cross-checked our work.

#### [Book Cover Generator](https://hello-world-coms6998.vercel.app/) & [Admin Panel](https://coms6998-admin-portal.vercel.app/) (In Progress)
Currently working on an AIGC app that helps users generate book covers and builds a community for users to share and rate generated book covers. Using Vercel to deploy the Next.js frontend, Supabase as database, git for version control, Google OAuth for verification, and Cursor for development. Image generation is currently supported by gpt-image-1-mini with usage limit and sana as fallback.

The admin panel contains the following functionalties: Overview (site data, including PV/UV, ai adoption rate, ai success rate, user journey, rating distribution, visit heatmap, etc.), Readers (manage user info), AI Covers (manage user posts), Ratings (details of ratings), Prompt chains & Prompt mix (edit prompt chains and adjust weight), Examples (used for few-shot prompting), Terms (define special terms for AI), Generated media & requests (view the details of each request, such as status, model used, created time, input,  etc.), LLM responses (records time consumption, prompt, storage url, etc.), Providers & Models (edit model providers and models), Allowed domains & Email whitelist (edit allowed emails for the public website).
The admin panel is not visable to non-superadmin users. 

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
