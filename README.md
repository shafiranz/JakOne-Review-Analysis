# JakOne-Review-Analysis
This project collects and analyzes user reviews of the JakOne Mobile app from Google Play. It scrapes reviews, categorizes them by issue type, and trains machine learning models (LSTM, SVM, Random Forest) to classify feedback and understand user sentiments effectively.

## Result
The data scraping successfully collected thousands of user reviews and categorized them into key problem areas such as technical bugs, UI/UX design, features, and transaction issues. Machine learning models (LSTM, SVM, and Random Forest) were trained to classify reviews, with the LSTM model showing the best performance in recognizing text patterns and sentiment.

## Findings & Insights
1. Frequent Technical Issues : Users often reported login errors, failed transactions, and app crashes.
2. UI/UX Concerns : Navigation and responsiveness were commonly criticized despite positive comments on design.
3. Feature Requests : Many reviews mentioned missing or outdated features.
4. Transaction Reliability Problems : Complaints about delayed transfers and balance errors were frequent.
5. Polarized Sentiment — Reviews showed both strong satisfaction and strong dissatisfaction, reflecting inconsistent user experiences.

## Recommendations
1. Fix Technical Instability : Resolve recurring crashes, login errors, and transaction bugs.
2. Improve User Interface : Simplify navigation and enhance performance for smoother interaction.
3. Enhance and Update Features : Add requested functions and maintain regular app updates.
4. Implement Real-Time Monitoring : Track errors and transactions dynamically to improve reliability.
5. Continue Sentiment Tracking : Regularly retrain the model with new reviews to monitor evolving user perceptions.
