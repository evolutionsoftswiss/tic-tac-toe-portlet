# Tic Tac Toe portlet
A Tic Tac Toe Portlet designed for liferay.

You find a running version on [evolutionsoft.ch](https://evolutionsoft.ch/liferay/tic-tac-toe).

## License
Tic Tac Toe portlet is provided under the GPL-3.0 or later GPL versions license.

## Known Issues
 * Users may receive a "Tic Tac Toe is temporary unavailable" message on the first access of the page. That is related to a liferay session issue and currently resolves by reloading the page.

## Installation instructions
You can download and install the latest release war file on a recent version of liferay.

## Implementation Information

### Alpha Beta search intelligence
Tic Tac Toe allows because of the simplicity and very limited number of possible game variations a full brute force search.
Here the advanced variation of mini max search alpha beta is used to additionally reduce the search space.

You can find the search intelligence source in *AlphaBetaSearch.java* in package *ch.evolutionsoft.game.tictactoe.treesearch*.

### Tic Tac Toe Frontend UI
The Tic Tac Toe portlet uses an Icefaces 4.3.0 JSF implementation to interact with users.
