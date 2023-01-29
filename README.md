# speed-typing
React. A game application that calculate speed typing rate of a person over a given time. The application counts, records and gives total of words. 
Using State and the updating State when typing words
Functions used: count words .trim() = does'nt count spaces when counting words;.split() = removes spaces in the words; .filter() = looks only at words not empty strings
Functions: to Reset Game() = startClock(), setTimeRunning(true), setText('');
Functions: EndGame() = setTimeRunning(false), SetWordCount(calculateWord())
Hooks: useEffect() Hook to set conditional time (start & end) in the game (to fetch data outside the boundaries of React)
Set up a disabled Game Button = which only activate when time is running and simultaneously disable with typing screen pad
