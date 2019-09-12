## Run Code

To run the code, in the terminal: - npm install - npm start

## Structure

I used React js as my main framework. The application was structured as followed:

          App component
        |               |
    SearchBar       Gnome List
                        |
                    GnomeCard

The App component has 2 child components which are, Search Bar and GnomeList. GnomeList has 1 child component which is GnomeCard.123

The SearchBar filters all results from json data and returns the search term to the app component which then sends the json objects filtered to the GnomeList. In the GnomeList each object is displayed using the GnomeCard component.

## Styling

I used bootstrap for most of the styling and then added some custom CSS for some extra changes I wanted to make.
