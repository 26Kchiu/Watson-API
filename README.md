# Watson-API
Watson API (Application Programming Interface) extracting PI (Personality Insights) from Twitter

Using Python programming language and leveraging Watson API this tool compares 2 separate Twitter accounts (User, Celebrity) and extracts the top 5 traits shared between them. The tool then calculates the probability of each profile exhibiting the given trait and compares the two against each other. The language capabilities of APIs were leveraged to retrieve insights from large, unstructured bodies of text. This is 1 of the 19 APIs available within the Watson Developer cloud. In this case, the Personality Insights API was utilized to extract the traits of the profile author.

The Result:

(Matched Personality Trait)-> (Probability of User Profile Exhibiting Given Trait)-> (Probability of Celebrity Profile Exhibiting given trait)-> (Compared Results)

Activity level 0.986268193916 -> 0.98416122099 -> 0.0021069729259

Achievement striving 0.926022825742 -> 0.923789104485 -> 0.00223372125713

Trust 0.959205422035 -> 0.967590703121 -> 0.00838528108622

Adventurousness 0.986383799727 -> 0.99693219047 -> 0.0105483907431

Anger 0.0435272899969 -> 0.0579794900791 -> 0.0144522000823
