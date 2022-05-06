### Hi there 👋

<!--
**ryansereno/ryansereno** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>Home</title>
        <link rel="stylesheet" href="styles.css" />
        <link href="Ac437_IBM_BIOS.ttf" />
        <link rel="image" href="/retro-stripe_right.png" />
    </head>
    <body>
        <div id="mainWindow">
            <header id="mainheader">
                <h1>
                    <a href="index.html">Ryan Sereno</a>
                </h1>
                <img id="retro-stripe" src="retro-stripe_right.png" alt="" />
            </header>

            <div id="menuBar">
                <ul>
                    <li><a href="index.html">[Home]</a></li>
                    <li><a href="link.test">[Blog]</a></li>
                    <li><a href="portfolio.html">[Portfolio]</a></li>
                    <li>
                        <a href="https://github.com/ryansereno">[GitHub]</a>
                    </li>
                    <li>
                        <a href="https://twitter.com/ry_serene">[Twitter]</a>
                    </li>
                    <li>
                        <a href="https://www.linkedin.com/in/serenoryan/"
                            >[LinkedIn]</a
                        >
                    </li>
                </ul>
            </div>
            <textarea
                placeholder="Run Haskell code here~

primes = filterPrime [2..]
  where filterPrime (p:xs) =
          p : filterPrime [x | x <- xs, x `mod` p /= 0]"
            ></textarea>
        </div>
    </body>
</html>
