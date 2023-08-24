# Forest-Damage-Study-A-Deep-Learning-Approach
This project represents an innovative application of deep learning to the critical environmental issue of forest damage. Utilizing aerophotos of forests and the U-net architecture, the study analyzes masked pairs of images with forest damages, providing insights into affected areas.

![Снимок экрана от 2023-08-24 04-48-53](https://github.com/D1H1/Forest-Damage-Study-A-Deep-Learning-Approach/assets/94292673/a53924e9-cb2d-4de8-b734-0b837c6b305f)

[Original Kaggle Notebook] (https://www.kaggle.com/code/davidhavrilenko/forest-damage-analisys-eripthack/notebook)

Key Components:
- Model Training: The U-net model was meticulously trained for 47 epochs at 49 seconds per epoch on a GPU P100.
- Data Source: The dataset was kindly provided by HackatonExpert Group and IPT faculty of Kyiv Polytechnic University, containing images only from November, leading to a biased dataset.
- Rapid Development: The project was developed in a Solo effort in just one day, demonstrating an agile approach to problem-solving.
- Recognition: The effort culminated in 1st place by jury points, reflecting the quality and innovation of the work.


Project Workflow:
- Image Masking: Utilizing the U-net model to create masks from pairs of images depicting forest damage.
- Damage Analysis: Applying the trained model to analyze remaining images, calculating percentages and square kilometers of damaged forests, both in general and by specific forest type.
- Visualization and Analysis: The next stage involves visualizing the results and conducting an in-depth analysis, providing valuable environmental insights.
- Geo-Coordinates and Statistics: The outcome of the study includes masks with geo-coordinates for integration into digital maps, and a dataframe containing comprehensive statistics about the damage in different zones.


Impact and Applications:
This project represents a significant step in the application of AI to environmental studies, potentially aiding in conservation efforts, policy-making, and future forest management planning. By transforming raw data into actionable insights, the study illustrates the power of technology to address real-world challenges.

Acknowledgements:
Special thanks to HackatonExpert Group and IPT faculty of Kyiv Polytechnic University for their invaluable support and collaboration.

![Снимок экрана от 2023-08-24 05-05-58](https://github.com/D1H1/Forest-Damage-Study-A-Deep-Learning-Approach/assets/94292673/13710ff3-425e-4f07-9e41-1c6dab45de87)

![Снимок экрана от 2023-08-24 05-06-18](https://github.com/D1H1/Forest-Damage-Study-A-Deep-Learning-Approach/assets/94292673/1344f517-711d-4c65-a541-e834f8596a8c)
