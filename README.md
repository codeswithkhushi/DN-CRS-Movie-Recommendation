# DN-CRS: Dual-Neighborhood Collaborative Filtering for Conversational Recommendation

## About the Project
DN-CRS is a conversational movie recommendation system that suggests movies based on user preferences and relevant past conversations. It combines conversation similarity, movie relationships, and popularity information to generate recommendations.

## Objectives
- Recommend movies relevant to user interests.
- Retrieve similar past conversations.
- Combine multiple signals to improve movie ranking.
- Extend recommendations by displaying a short story or synopsis for each movie.

## How It Works
1. **User Input:** The user shares their interests or movie preferences.
2. **Conversation Retrieval:** The system finds similar past conversations.
3. **Movie Ranking:** It combines dialogue similarity, item-based collaborative filtering, and popularity signals.
4. **Recommendation Output:** The system returns ranked movie suggestions.
5. **Movie Synopsis (Planned):** Display a short story or synopsis alongside each recommended movie. This feature requires implementation or verification.

## Key Features
- Conversational movie recommendations
- Similar conversation retrieval
- Item-based collaborative filtering
- Popularity-aware ranking
- Planned movie synopsis display

## Technologies Used
- Python
- MiniLM embeddings
- BM25 retrieval
- Collaborative Filtering
- ReDial and INSPIRED datasets

## Expected Output
The system provides a ranked list of movie recommendations. A future enhancement is to show each movie's title together with a short synopsis to help users understand its story.

## Future Scope
- Integrate movie synopsis data.
- Improve personalization and ranking.
- Develop a more user-friendly interface.

## Conclusion
DN-CRS combines conversational context and movie relationships to recommend relevant movies. Adding movie synopses can make the recommendations more informative and useful.

## Disclaimer
The movie synopsis display is described as a planned enhancement until its implementation is verified in the project code.
