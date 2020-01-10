# RComextSwissRe

## Description Bob's burgeoning fortune
During the day Bob runs a burger stall. Last year he made a healthy profit, which he has invested in crypto coins. Infact Bob now has so many
coins he is finding it difficult to track their value.
Bob keeps a .txt file with the crypto symbol and the quantity he holds. An example file contents is:

    BTC=10
    ETH=5
    XRP=2000
During a quiet spell at the stall Bob stumbled upon a free to use REST API. For example, to find the current EUR price of Bitcoin he could make
this call:

    https://min-api.cryptocompare.com/data/price?fsym=BTC&tsyms=EUR


Bob has Java 8 installed on his work laptop. He would like to run a simple program which reads his input file and nicely prints the current EUR
value of each coin he holds e.g. if BTC is worth 5 EUR, it would show 50 EUR based on the sample above.
Bob also wants the program to show the total value of all his investments.


#### Tasks
- write a simple program which prints the value of Bob's crypto portfolio

- the input to the program is a file called bobs_crypto.txt


### Command Line CLI
Running the Main class it should show a menu that looks as follows.
    
    Welcome to this sorting Bob's burgeoning fortune challenge.
    Choose an option.
    1. Calculate default, file under resources folder.
    2. Calculate but specify Bob´s file location.
    If you want to exit click 0
    
    Choose menu item: 

#### Miscellaneus:
 
- Java 8 
- JUnit5
- Maven
