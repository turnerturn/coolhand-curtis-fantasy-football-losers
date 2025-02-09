# Fantasy Football Loser Lounge

This is the lounge for all last place winners of the "Cool Hand Curtis" fantasy football league.

## How do I add new last place winners to the plaque?

To add a new last place winner to the plaque, follow these steps:

1. Navigate to the GitHub repository at the following URL: [https://github.com/turnerturn/coolhand-curtis-fantasy-football-losers](https://github.com/turnerturn/coolhand-curtis-fantasy-football-losers)

2. Create a new account if you haven't already signed up for GitHub.

3. Login with your GitHub account.

4. Navigate to our repository's `index.html` at [https://github.com/turnerturn/coolhand-curtis-fantasy-football-losers/blob/main/index.html](https://github.com/turnerturn/coolhand-curtis-fantasy-football-losers/blob/main/index.html)

5. Click the edit icon aligned in the top right of the file's header panel.

6. Find where we define our accolades JSON object by finding the instance of text `const accolades`.

7. Scroll through the lines following our accolades. This JSON array defines our timeline's accolades. Go to the bottom of this JSON array and add a comma to the last item and insert your intended details. (Example for appending item for the year of 2025 below.)

    ```json
    ....,
    {
        "year": 2024,

        "owner": "Aaron Grippando",
        "teamName": "A Grip",
        "memeUrl": "https://g.espncdn.com/lm-static/logo-packs/ffl/BoneHeads-ToddDetwiler/BoneHeads-01c.svg",
        "quote": "You’ve turned losing into an art form!"
    }
    , {
        "year": 2025,
        "owner": "John Doe",
        "teamName": "Not A Team",
        "memeUrl": "https://i.imgflip.com/26am.jpg",
        "quote": "The world's biggest loser"
    }
    ```

8. Click Commit Changes (Green button on top right of the web interface).

9. Navigate through the default options and prompts... (make sure to "Commit directly to the main branch").

10. Our web page should be updated with your changes shortly. If help is needed, contact info is provided at [https://github.com/turnerturn](https://github.com/turnerturn)
