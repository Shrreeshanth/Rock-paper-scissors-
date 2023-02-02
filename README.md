# Rock-paper-scissors-
Game py

                                        #Game - Rock,Paper,Scissors
                                        #By S.S.SHRREESHANTH
                                        #(First Game created using VS - Code , Python progarming language)
  

#Used modules:
import random

#Gamelists:

#Inputs(controls) for game:
Gamelist1=['R','P','S']



#Variable used for controlling looping times:
t=1



#Scores: 
   
# #Human Score
i=0

#Computer Score
c=0

#Number of Rounds
q=10





#Gamefunctions:

#Function for Restarting the Game:
def ResGameRPS():
    print('')
    print("Do You wish to Restart the Game - Rock,Paper,Scissors ??")
    print("Yes or NO ??")
    Restart=input()
    if  Restart=="Yes":
        print('')
        GameRPS()
    elif Restart=="yes":
        print('')
        GameRPS()
    elif Restart=="YES":
        print('')
        GameRPS()
    elif Restart=="No":
        exit()
    elif Restart=="NO":
        exit()
    elif Restart=="no":
        exit()
    else:
        print("Error! Enter either Yes or No")
        print("")
        ResGameRPS()
  
#Function used for looping - Rounds (10 times):
def Roundsq():
    global q
    q=10
    print('')
    while 0<q<2:
        q=q-1
        print('Number of Rounds left :',q)
        print('')
        print('')
        print('==========================================================================  FINAL RESULTS !  ===========================================================================')
        if i<c:
            print('You lost. Better luck next time',Name ,'. Computer Won the Game !')
            print('Compuer has won the Game by', c ,'Point(s)')
        elif i==c:
            print('The scores are level . hahahaha...!!!  There is a Tie between', Name ,'and Computer')
            print('You and Compuer Tied. Try to Score more than the Computer next time...')
        else:
            print('Congratulations !!!..', Name ,'won the Game.')
            print('You won the Game by', i ,'Point(s)')
        print('')
        print('')
        print('============================================================================  GAME OVER !  =============================================================================')
        print('')
        print('')
        ResGameRPS()
        break
    while 1<q<3:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 2<q<4:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 3<q<5:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 4<q<6:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 5<q<7:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 6<q<8:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 7<q<9:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 8<q<10:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 9<q<11:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break

#Function for looping - Rounds (10 times) - loops:
def Roundsq_loops():
    global q
    print('')
    while 0<q<2:
        q=q-1
        print('Number of Rounds left :',q)
        print('')
        print('')
        print('==========================================================================  FINAL RESULTS !  ===========================================================================')
        print('')
        print('')
        if i<c:
            print('                                                    You lost. Better luck next time',Name ,'. Computer Won the Game !')
            print('                                                              Compuer has won the Game by', c ,'Point(s)')
        elif i==c:
            print('                                           The scores are level . hahahaha...!!!  There is a Tie between', Name ,'and Computer')
            print('                                                   You and Compuer Tied. Try to Score more than the Computer next time...')
        else:
            print('                                                        Congratulations !!!..', Name ,'won the Game.')
            print('                                                             You won the Game by', i ,'Point(s)')
        print('')
        print('')
        print('============================================================================  GAME OVER !  =============================================================================')
        print('')
        print('')
        ResGameRPS()
        break  
    while 1<q<3:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 2<q<4:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 3<q<5:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 4<q<6:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 5<q<7:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 6<q<8:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 7<q<9:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 8<q<10:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break
    while 9<q<11:
        q=q-1
        print('Number of Rounds left :',q)
        GameRPSloop()
        break

#Function for Gamecond() - loops:
def Gamecond_loops():
    global t
    global i 
    global c
    if Human_choice==Computer_choice:
        print('Its a Tie')
        print('')
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        print('')
        Roundsq_loops()
        

            

    elif Human_choice=='R':
        if Computer_choice=='P':
            print('Computer won, Better luck next time.')
            while Human_choice=='R':
                while Computer_choice=='P':
                    value_c_loops()
                    break

        elif Computer_choice=='S':
            print('You won, Super! ')
            while Human_choice=='R':
                while Computer_choice=='S':
                    value_i_loops()       
                    break

    elif Human_choice=='P':
        if Computer_choice=='S':
            print('Computer won, Better luck next time.')
            while Human_choice=='P':
                while Computer_choice=='S':
                    value_c_loops()    
                    break

        elif Computer_choice=='R':
            print('You won, Super! ')
            while Human_choice=='P':
                while Computer_choice=='R':
                    value_i_loops()
                    break

    elif Human_choice=='S':
        if Computer_choice=='R':
            print('Computer won, Better luck next time.')
            while Human_choice=='S':
                while Computer_choice=='R':
                    value_c_loops() 
                    break

        elif Computer_choice=='P':
            print('You won, Super! ')
            while Human_choice=='S':
                while Computer_choice=='P':
                    value_i_loops()
                    break

    else:
        print( 'Error !  Please enter your choice from the following - R or P or S')
        print('REQUESTED - To Restart the Game')
        print('')
        print('')
        ResGameRPS() 

#Function for Human_score:
#Used variable 'i':
def value_i():
    global i
    i=0
    global c 
    c=0
    while 9<i<11:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 8<i<10:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 7<i<9:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 6<i<8:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 5<i<7:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 4<i<6:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 3<i<5:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 2<i<4:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 1<i<3:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 0<i<2:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while i<1:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break

#Function for Computer_score:
#Used variable 'c':
def value_c():
    global c
    c=0
    global i 
    i=0
    while 9<c<11:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 8<c<10:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 7<c<9:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 6<c<8:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 5<c<7:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 4<i<6:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 3<c<5:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 2<c<4:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 1<c<3:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while 0<c<2:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break
    while c<1:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq()
        break

#Function for Human_score:
#Used variable 'i' - loops:
def value_i_loops():
    global i
    global c
    while 9<i<11:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 8<i<10:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 7<i<9:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 6<i<8:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 5<i<7:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 4<i<6:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 3<i<5:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 2<i<4:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 1<i<3:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 0<i<2:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while i<1:
        i=i+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break

#Function for Computer_score:
#Used variable 'c' - loops:
def value_c_loops():
    global c
    global i
    while 9<c<11:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 8<c<10:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 7<c<9:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 6<c<8:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 5<c<7:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 4<i<6:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 3<c<5:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 2<c<4:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 1<c<3:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while 0<c<2:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break
    while c<1:
        c=c+1
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        Roundsq_loops()
        break

#Function for Indroduction of user - Name:
def Game_RPS_F():
    print('==========================================================================  GAME - ROCK,PAPER,SCISSOR  =================================================================')
    print('Welcome to the Game - Rock,Paper,Scissor')
    print('by S.S.SHRREESHANTH')
    print('')
    def Nameinput():
        print("Whats your name?")
        print('')
        global Name
        Name=input()
        if Name=="":
            print('Error ! Invalid input . Enter a Valid Name !!')
            print('')
            print('')
            Nameinput()
        else:
            print("Your name is",Name)
            print('')
            print('Hi', Name, 'welcome to the Game - Rock,Paper,Scissor')
            print('')
            print('')
    Nameinput()
    def Age():
        print('whats your age?')
        print('')
        age=int(input())

        if 0<age<100:
            print('your age is', age)
            print('')
            Gender()

        elif age==100:
            print('Really?, your age is 100? Its Shocking. Wow. Its ok lets move to the next part')
            print('')
            Gender()
        elif age>100:
            print('Really?, your age is ',age,'? Its Shocking. Wow. Its ok lets move to the next part')
            print('')
            Gender()
        else:
            print('Error! please enter your real age in whole number.')
            print('')
            Age()
    Age()

#Function for Strating Game:
def Gamestart():
    print(Name ,'are you ready to play the Game - Rock,Paper,Scissors ??')
    print('Yes or No ??')
    print('')
    Readygame=input()

    if Readygame=='YES':
        print('')
        print('WOW   Lets start to play the Game - Rock,Paper,Scissors')
        print('')
        Gamerules()
    elif Readygame=='yes':
        print('')
        print('WOW   Lets start to play the Game - Rock,Paper,Scissors')
        print('')
        Gamerules()
    elif Readygame=='Yes':
        print('')
        print('WOW   Lets start to play the Game - Rock,Paper,Scissors')
        print('')
        Gamerules()
    elif Readygame=='No':
        print('')
        print('Thanks for visiting comeback again')
        print('Press Enter key to exit')
        input()       
    elif Readygame=='NO':
        print('')
        print('Thanks for visiting comeback again')
        print('Press Enter key to exit')
        input()
    elif Readygame=='no':
        print('')
        print('Thanks for visiting comeback again')
        print('Press Enter key to exit')
        input()
    else:
        print('Error ! Invalid Input. Please enter either Yes or No !!')
        print('')
        print('')
        Gamestart()

#Function for GameRPS - taking inputs for GameRPS:
def GameRPS():
    print('')
    print('Press Enter key to start the Game')
    input()
    
    print('')
    print('')
    print('Type R or P or S')
    global Human_choice
    Human_choice=input('     Your choice : ')
    global Computer_choice
    Computer_choice=random.choice(Gamelist1)
    print(' Computer choice :',Computer_choice)
    print('')
    Gamecond()

#Function for GameRPS for looping 10times:
def GameRPSloop():
    print('')
    print('')
    print('Type R or P or S')
    global Human_choice
    Human_choice=input('     Your choice : ')
    global Computer_choice
    Computer_choice=random.choice(Gamelist1)
    print(' Computer choice :',Computer_choice)
    print('')
    Gamecond_loops()

#Function for Gamecond_loops:
def Gamecond():
    t=1
    

    
    if Human_choice==Computer_choice:
        print('Its a Tie')
        print('')
        print('')
        print('Your Score =', i)
        print('Computer Score =', c)
        print('')
        Roundsq()
        
        

            

    elif Human_choice=='R':
        if Computer_choice=='P':
            print('Computer won, Better luck next time.')
            while Human_choice=='R':
                while Computer_choice=='P':
                    t=t+1
                    while 1<t<3:
                        value_c()
                        break
                                    
            
        elif Computer_choice=='S':
            print('You won, Super! ')
            while Human_choice=='R':
                while Computer_choice=='S':
                    t=t+1
                    while 1<t<3:
                        value_i()
                        break          
            

    elif Human_choice=='P':
        if Computer_choice=='S':
            print('Computer won, Better luck next time.')
            while Human_choice=='P':
                while Computer_choice=='S':
                    t=t+1
                    while 1<t<3:
                        value_c()
                        break        
            

        elif Computer_choice=='R':
            print('You won, Super! ')
            while Human_choice=='P':
                while Computer_choice=='R':
                    t=t+1
                    while 1<t<3:
                        value_i()
                        break         
            

    elif Human_choice=='S':
        if Computer_choice=='R':
            print('Computer won, Better luck next time.')
            while Human_choice=='S':
                while Computer_choice=='R':
                    value_c()            
            

        elif Computer_choice=='P':
            print('You won, Super! ')
            while Human_choice=='S':
                while Computer_choice=='P':
                    t=t+1
                    while 1<t<3:
                        value_i()
                        break
                        
            

    else:
        print( 'Error !  Please enter your choice from the following - R or P or S')
        print('REQUESTED - To Restart the Game')
        print('')
        print('')
        ResGameRPS()

#Function for gender - input from user:
def Gender():
    print('')
    print('What is your Gender?')
    print('')
    Gender1=input()
    if Gender1=='Male':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    elif Gender1=='MALE':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    elif Gender1=='male':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    elif Gender1=='Female':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    elif Gender1=='FEMALE':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    elif Gender1=='female':
        print('Your Gender is' , Gender1)
        print('')
        print('')
        Gamestart()
    else:
        print('Error ! Your input is invalid. Enter either Male or Female to proceed !!')
        print('')
        Gender()

#Function for Gamerules:
def Gamerules():
        print('')
        print('Rules:')
        print('')
        print('  Controls:')
        print('    Rock     - R \n    Paper    - P \n    Scissor  - S')
        print('')
        print('  Number of Rounds : 10')
        print('')
        print('About Game - Rock,Paper,Scissor:')
        print('\n If \n Your choice = R(Rock)     &    Computer choice = P(Paper)   \n Then Computer won ')
        print('\n If \n Your choice = S(Scissor)  &    Computer choice = R(Rock)    \n Then Computer won ')
        print('\n If \n Your choice = P(Paper)    &    Computer choice = S(Scissor) \n Then Computer won ')
        print('\n If \n Your choice = S(Scissor)  &    Computer choice = P(Paper)   \n Then   You    won ')
        print('\n If \n Your choice = P(Paper)    &    Computer choice = R(Rock)    \n Then   You    won ')
        print('\n If \n Your choice = R(Rock)     &    Computer choice = S(Scissor) \n Then   You    won ')
        print('\n If \n Your choice = R(Rock)     &    Computer choice = R(Rock)    \n Then Tie ')
        print('\n If \n Your choice = P(Paper)    &    Computer choice = P(Paper)   \n Then Tie ')
        print('\n If \n Your choice = S(Scissor)  &    Computer choice = S(Scissor) \n Then Tie ')
        print('')
        print('  HINT    - View in Fullscreen.')
        print('  NOTE    - Dont skip the Rules ! ...')
        print('REQUESTED - To read Rules before starting the Game ! ...')
        print('')
        GameRPS()


#Main Function called:
Game_RPS_F()


#A small Game - Rock,paper,scissor
#Done by S.S.SHRREESHANTH

#About "Game - Rock,paper,scissor" :

#Programing done in VS - code
#Programing Language used - Python
#4 days of writing code:
#     Started Coding  on 27/10/2020
#     Finished Coding on 30/10/2020


#Strictly not copied from anyone or anywhere !..
#Ask permission to the owner before copying or using this code !......
#If the owner agree and you are also wiling to copy the code ....  use it in a fair way



#Thanks for attending the quiz and viewing the codes

#Thank you , Have a nice day , Byeee!!!!!........

#========================================== THE END ! =========================================================
