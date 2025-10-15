# Youtube_Video_Views_Prediction

This is a class project from Spring 2025 BA865 (Introduction to Neural Networks). We used the YouTube API to scrape the metadata of 12,000 videos, including thumbnail, title, views, channel name, channel followers, publish time, etc. Please see `youtube_cleaned_success_only.csv` for reference. All videos were at least 2 weeks old at the time we scraped them to make sure the view counts had matured.

With the data we scraped, we were trying to extract features that could accurately predict view counts based on metadata. The goal is to help content creators adjust the things under their control—thumbnails, title, publish time, etc.—to earn more views when publishing a video.

We tried an MLP model and a CNN for thumbnail processing. We also used SHAP for model interpretability. We noticed that having faces in thumbnails helps with higher view counts. Also, adding special symbols in the title can help improve views too.

We also integrated our model into Streamlit to demonstrate how it can predict view counts based on metadata inputs: [https://youtubeprediction-aij9p3nn3bmkcvpcnukuh2.streamlit.app/](https://youtubeprediction-aij9p3nn3bmkcvpcnukuh2.streamlit.app/) (the app may be inactive due to prolonged inactivity).

This is a team project with Manyi Hong, Wenxin Liang, and Shuomeng Guan

