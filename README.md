# mekuriawase

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A memory matching game that uses tourism open data from Japan. Flip the cards to find matching pairs of tourist spots, revealing their names and photos.


![Screenshot of the mekuriawase game board with several cards flipped over, showing images of tourist locations.](https://fukuno.jig.jp/2014/mekuriawaseodp.jpg)


## Demo

Play the game live at: **https://code4fukui.github.io/mekuriawase/**

## Features

-   **Memory Game:** A classic card-matching game using images and names of real tourist locations.
-   **Dynamic Data:** Pulls data directly from a live open data source, providing a variety of locations.
-   **Randomized Layout:** The card positions are shuffled at the start of each game.
-   **Location Finder:** Once a pair is matched, a "ココに行く" (Go Here) button appears, which opens a map of the location in a new tab.
-   **Timed Challenge:** A "Clear Time" is displayed upon successfully matching all pairs.

## How to Play

1.  Open the [demo URL](https://code4fukui.github.io/mekuriawase/).
2.  Click on any two cards to flip them over and see if they match.
3.  If the cards match, they remain face up. If not, they flip back over.
4.  Continue until all pairs are found.
5.  Click the "リトライ！" (Retry!) button to start a new game with a new set of shuffled cards.

## Data Source

This project uses the [Open Data Platform (ODP)](https://odp.jig.jp/) SPARQL endpoint to fetch data on civic points of interest in Japan.

## Attribution

This application was created by Taisuke Fukuno as part of the [一日一創 (One Creation a Day)](http://fukuno.jig.jp/757) project.

## License

This project is available under the [MIT License](LICENSE).