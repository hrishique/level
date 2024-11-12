# level
A telegram mini app that helps users to get which level of understanding they have on Cairo with a gamefied experience. 

An app that will help people to learn cairo and also compete with there friends and win some rewards. <br>
** They just need to enter their proficiency with the language and then the quiz starts.<br>
** It leverages the Power of AI to give you suitable explanations for the questions that you answered incorrectly and also alter the questions that follow by lowering the difficulty level of the following questions.<br>

# WorkFLOW

User opens telegram and runs the Bot.<br>
He is prompted to connect his wallet.<br>
User is asked to select a level among ( Beginner, Intermediate, Advanced).<br>
He can take a simple quiz or Challenge a friend.<br>
If he answers the question correctly, he gets some points and moves on to the next level the quicker he answers the more points he get.<br>
If he answers the question with a wrong option we take use of AI model and give them a detailed explanation about the question and also give them the correct answer.<br>
If user gives a wrong answer then his level is reiterated and a relatively easier question is asked.<br>
At the end of the quiz based on the points users might get tokens.<br>
If the user is challenging a friend they can both stake tokens and then at the end whoever has higher number of points wins the quiz and his wallet is credited with the tokens.<br>


# Resources
*To implement AI we will be using the GIZA SDK that uses Cairo For **Zk-ML** <br>
[Giza video Tutorial](https://www.youtube.com/watch?v=t1Z5Anx_t6c)
[Giza Github Repo](https://github.com/gizatechxyz)
[Giza Official website](https://gizatech.xyz/)


*For connecting wallet we aill use Argent Telegram sdk.<br>
[Using Argent wallet with telegram](https://www.argent.xyz/blog/how-to-use-argent-telegram-wallet) 

