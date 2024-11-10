Recommender System: Collaborative vs. Content-Based Filtering
1. Collaborative Filtering (CF)
Concept: Recommends items based on user interactions and preferences. It assumes that similar users will have similar preferences.
Types:
User-Based: Finds users with similar preferences and recommends what those users liked.
Item-Based: Finds similar items based on user ratings; recommends items similar to those the user liked.
Pros:
No need for item features (metadata).
Can discover complex user-item relationships.
Cons:
Struggles with new users/items (cold start problem).
Requires large amounts of user interaction data.

2. Content-Based Filtering
Concept: Recommends items based on item features and the user’s profile, which includes previously liked items.
How It Works:
Analyzes item characteristics (e.g., genre, keywords).
Matches these features with the user’s preferences.
Pros:
Effective for new users (if they have some initial data).
Explains recommendations based on item features.
Cons:
Limited to recommending items similar to what the user already likes.
Requires detailed item metadata.
Use Case Examples:

Collaborative Filtering: Netflix recommending shows based on similar users' viewing history.
Content-Based Filtering: Spotify suggesting songs based on the genre and artist similar to previously liked tracks.
