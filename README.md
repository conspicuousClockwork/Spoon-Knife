### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:

charCount = (num) => [...num].reverse().reduce((ac, ch) => ((ac[1] && ac[0].push(ch)) || (((ch.charCodeAt()+1 <= 90) && (ac[0].push(String.fromCharCode(ch.charCodeAt()+1)) && (ac[1] = true))) || (ac[0].push('A') && ((ac[0].length === num.length && ac[0].push('A')) || true)))) && ac,[[], false])[0].reverse().join('');
