1. PORTs
RPC Port: 9999 (Chagne to whatever you want. eg, 15497)
Network Port: 15493

2. Build - Unix/Linux
- cd src
- \rm -rf obj      // Delete object directory, if exists.
- mkdir obj        // Create it back.
- make -j2 -f makefile.unix

You can find BurnCoind file in the same directory.
Copy it wherever you want. e.g, 'copy BurnCoind /usr/bin/'

3. Build - Windows QT
You can build it with QT. As one example, 
- Install QTCreator.
- Load qt.pro project file.
- Run or Build 

(You may need dependent library files for Building. Check it out in qt.pro file.)

4. Run and Stop
- Just run it : /usr/bin/BurnCoind
- To stop: /usr/bin/BurnCoind stop


5. Data directory

The default data folder is as follows,
- $HOME/.BurnCoinNew  (in Unix, Linux, Mac)


Date: 2018.09.06
