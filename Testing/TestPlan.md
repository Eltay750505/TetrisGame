# Testing plan
 ### Content
  1. [Introduction](#1)
  2. [Testing object](#2)
  3. [Risks](#4)
  4. [Aspects of testing](#5)<br>
  5. [Approaches to testing](#6)
  6. [Presentation of results](#7)
  7. [Conclusion](#8)
  <a name="1"></a>
 ## 1. Introduction
The content of this document describes the test plan for the Tetris desktop application. The purpose of testing is to test the application in accordance with SRS.
<a name="2"></a>
 ## 2. Testing object
### 1. Functional suitability
-   #### functional completeness
    The feature set of the application should cover all the features described in the SRS.
-   #### Functional correctness
    The application must perform all declared functions correctly.
-   #### Functional feasibility.
    There are no non-declared functions that would prevent the application from performing the originally assigned tasks.
### 2. Usability
-   #### The accessibility of the user interface
    Object controls must always be available to the user
-   #### Urgency
    All changes happen in real time
<a name="3"></a>
## 3. Risks
The risks include:
- If there is no JVM on the device, the application will not start
- The processing speed of game logic depends on the processor of the device
<a name="4"></a>
 ## 4. Aspects of testing
During testing, the implementation of the main functions of the application, which include:
1. Start new game
2. Lose the game
3. Playing the game
4. Pause the game
5. Watch the scoreboard

### Functional requirement
#### 1. Start new game
This use case should be tested when:
- Enabled automatic game mode
- Controlled game mode

#### 2. Lose the game
When one of the blocks reaches the ceiling, the game ends

#### 3. Playing the game
This use case should be tested for the ability to test the gameplay.

#### 4. Pause the game
This use case should be tested when you press pause.

#### 5. Watch the scoreboard
This use case should be tested during the draw by clicking on the score button.

### Нефункциональные требования:
#### 1. Clear gameplay
Understanding what to do after one or three games.

#### 2. Performance
No friezes while using the app

<a name="5"></a>
## 5. Approaches to testing
To test an application, you must manually test every aspect of the testing.

<a name="6"></a>
## 6. Presentation of results
The test results are presented in the [doc](https://github.com/Eltay750505/TetrisGame/blob/master/Testing/TestResult.md).

<a name="7"></a>
## 7. Conclusion
This test plan allows you to test the main functionality of the application. Successful completion of all tests with a high probability can be said about good performance, and that this software works correctly.

    
