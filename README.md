# Football Transfer Market Virtual Assistant

Final project for the Building AI course

## Summary

This project aims to develop a virtual assistant that supports football club management in transfer market decision-making. It leverages AI to analyze player performance, price, club budget, transfer philosophy, and socio-economic context to enhance scouting and recruitment.

## Background

Football clubs often make transfer decisions based on partial information, overlooking key factors that could make certain players stand out. This project seeks to address this issue by providing a comprehensive analysis of potential signings and evaluating the feasibility of acquiring a specific player.

Problems addressed:
* Decision-making in player recruitment often lacks a holistic approach.
* Clubs may struggle to identify players who fit their philosophy and financial situation.
* External factors, such as socio-economic context, are rarely considered in transfer evaluations.

## How is it used?

The virtual assistant will primarily be used internally by football clubs. It will process private club data, including budgets, philosophies, and needs, while integrating third-party data from providers like Wyscout, Opta, and Transfermarkt.

Usage scenario:
1. Club management inputs specific requirements and constraints.
2. The AI assistant searches for potential players that match the club's needs.
3. The assistant evaluates the feasibility of acquiring a chosen player.
4. Management reviews insights to support decision-making.

## Data sources and AI methods

The model will use data from:
* Third-party football data providers: [Wyscout](https://wyscout.com/), [Opta](https://www.statsperform.com/opta), [Transfermarkt](https://www.transfermarkt.com/)
* Club-specific financial and strategic data
* External context that could be relevant

AI methods:
* Machine learning models for performance evaluation
* Natural Language Processing (NLP) for contextual understanding
* Optimization algorithms for financial feasibility assessment

## Challenges

* The assistant should not be viewed as the ultimate authority on transfers but rather as a tool to enhance decision-making.
* Contextual and human factors influencing transfers may not always be quantifiable.
* Data integration from various sources while maintaining accuracy and security.

## What next?

The next steps involve structuring the necessary data and developing a robust model for the assistant. Future improvements may include:
* Expanding contextual understanding by integrating sentiment analysis on player behavior and public perception.
* Enhancing predictive capabilities to anticipate market trends.
* Collaborating with clubs to refine the model based on real-world feedback.

