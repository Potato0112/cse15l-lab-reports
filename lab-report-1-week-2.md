# CSE 15L Lab Report 1

# Step 1: Installing VScode
1. go to the VScode website
2. download VScode 
3. create cse15L folder somewhere on computer
4. go into terminal in VScode and cd to cse15L folder
5. should look like this(disregard code shown):

![Image](screen1.png)

# Step 2: Remotely Connecting
1. install openSSH
2. find your cse15l account [here](https://sdacs.ucsd.edu/~icc/index.php)
3. open terminal in VScode and type: ```$ ssh cs15lsp22zz@ieng6.ucsd.edu ``` (NOTE: change 2 letters before "@" to ones shown in account lookup)
4. when prompted, type "yes"
5. now the the computer is connected to a computer in the CSE basement and commands can be remotely run

![Image](screen2.png)

# Step 3: Run Some Commands
1. in terminal, type in "cd", "ls", "pwd" "mkdir" and "cp" on local computer and after sshing into basement computer
2. record any errors that occur

![Image](screen3.png)

# Step 4: Move files over ssh using scp
1. open terminal on client computer and type ```scp```
2. make local file called ```WhereAmI.java``` and put
```  
class WhereAmI {
  public static void main(String[] args) {
    System.out.println(System.getProperty("os.name"));
    System.out.println(System.getProperty("user.name"));
    System.out.println(System.getProperty("user.home"));
    System.out.println(System.getProperty("user.dir"));
  }
}

```


