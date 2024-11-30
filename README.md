

<h1>Candy Game in Turbo C++</h1>

<h2>Overview:</h2>
<p>This project is a simple, console-based Candy Game developed using Turbo C++. The game involves a box that moves left and right to catch falling candies. Players must use the keyboard to control the box and catch as many candies as possible to increase their score. The game also includes a lifeline feature, where the player loses a lifeline each time they miss a candy. The game ends when the player runs out of lifelines.</p>

<h2>Key Features:</h2>

<h3>Time Tracking:</h3>
<ul>
    <li>The game does not have a timer, but it tracks the player's score and lifelines.</li>
    <li>The game updates in real-time as the player controls the box to catch the falling candies.</li>
</ul>

<h3>User Controls:</h3>

<h4>Move Box:</h4>
<ul>
    <li>Users can move the box left and right by pressing the "a" or "d" keys respectively.</li>
    <li>The box moves across the screen to catch falling candies.</li>
</ul>

<h4>Game Actions:</h4>
<ul>
    <li>When a candy reaches the bottom of the screen, the game checks if the box caught it or missed it.</li>
    <li>If the candy is caught, the player earns a point.</li>
    <li>If the candy is missed, the player loses a lifeline.</li>
    <li>The game ends when the player runs out of lifelines.</li>
</ul>

<h3>Game Logic:</h3>

<h4>Score and Lifelines:</h4>
<ul>
    <li>The player's score increases by one every time a candy is successfully caught.</li>
    <li>The player starts with three lifelines. Each time a candy is missed, a lifeline is lost.</li>
    <li>The game ends when the player has no lifelines left.</li>
</ul>

<h4>Box Movement:</h4>
<ul>
    <li>The box is controlled by the player using the "a" and "d" keys to move it left and right, respectively.</li>
    <li>The box moves horizontally within the limits of the screen, preventing it from going off-screen.</li>
</ul>

<h3>Input Validation:</h3>
<ul>
    <li>The program ensures that the user inputs valid controls (i.e., "a" or "d" to move the box, "x" to exit the game).</li>
    <li>If the user presses an invalid key, the game ignores the input and continues running.</li>
</ul>

<h2>Technologies:</h2>

<h3>Turbo C++:</h3>
<ul>
    <li>The game is developed using the Turbo C++ environment, utilizing functions like <code>clrscr()</code>, <code>gotoxy()</code>, and <code>kbhit()</code> for handling screen output and user input.</li>
    <li>The game logic relies on basic control flow and user input handling to provide an interactive gaming experience.</li>
</ul>

<h3>Game Features in C++:</h3>
<ul>
    <li>The game uses simple graphical representation by printing characters to the console to depict the box and candies.</li>
    <li>The game's interface includes a text-based score display and updates the position of the box and candies on the screen in real-time.</li>
</ul>

<h2>How to Play:</h2>
<ol>
    <li>Start the game by running the <code>CandyGame.cpp</code> file in your Turbo C++ IDE or compiler.</li>
    <li>The program will display the following options:
        <ul>
            <li><strong>Move Left (a)</strong> – Moves the box to the left.</li>
            <li><strong>Move Right (d)</strong> – Moves the box to the right.</li>
            <li><strong>Exit (x)</strong> – Exits the game.</li>
        </ul>
    </li>
    <li>The goal of the game is to catch as many falling candies as possible by moving the box left or right.</li>
    <li>Each successful candy catch adds to the score, and each missed candy deducts a lifeline.</li>
    <li>The game ends when the player runs out of lifelines, and the final score is displayed.</li>
</ol>

<h2>How to Run:</h2>
<ol>
    <li>Clone this repository to your local machine or create a new project in your Turbo C++ IDE (e.g., Turbo C++ 3.0).</li>
    <li>Copy the C++ code into a new file named <code>CandyGame.cpp</code>.</li>
    <li>Compile and run the <code>CandyGame.cpp</code> file to start playing the Candy Game.</li>
</ol>

