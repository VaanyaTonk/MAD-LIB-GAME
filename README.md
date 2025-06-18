# MAD-LIB-GAME
Create your own hilarious story with this fun and quick fill-in-the-blank game — just add your words and watch the madness unfold!
WHAT IS A MAD-LIB GAME?

Imagine being asked to blurt out a bunch of random words like an animal, a weird food, or a silly exclamation — without knowing what they’re for. Then suddenly, those words pop up in a super ridiculous and funny story. That’s Mad Libs!

It’s like story-making, but with surprises and laughter baked in.

HOW DOES IT WORK IN JAVA?

So, in Java, we can turn this fun idea into a simple program that asks you for words and then uses them to complete a silly story. Here's how it all works behind the scenes:

STEPS:

We start by creating a Scanner – this lets our program take input from the user:

Scanner scanner = new Scanner(System.in);

The game asks you questions, like “Give me an animal” or “What’s your favorite food?”
Your answers are saved in variables like:

String animal = scanner.nextLine();

After you answer all the prompts, the story is printed, with your words filling in the blanks. That’s where the chaos begins! 😄
Finally, we close the Scanner:

scanner.close();

WHY IS IT FUN?

Because it’s completely unpredictable! Your innocent choice of "toaster" or "pickles" might end up in a royal speech or a romantic proposal in the story. The weirder your words, the funnier it gets.

QUICK EXAMPLE:

Let’s say you entered:

Emotion: sleepy

Animal: llama

Food: jellybeans

Your story might go:

“One day, I woke up feeling really sleepy and realized I had turned into a giant llama! I slipped on some jellybeans and shouted ‘WHEEEE!’”

Totally absurd. And that’s the point!


