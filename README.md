# git-go
Git-Go is a supposed cross platform website blocker that will block any web domain by looping the connection to the loopback
```
 ______ _____ _______      ______  _____ 
 |  ____   |      |    ___ |  ____ |     |
 |_____| __|__    |        |_____| |_____|
-----------------------------------------------------------------------------
_________________________________________________
|System Name             |=> Linux
|Node/System Name        |=> X43DW91
|System Current Version  |=> #3 SMP Tue Nov 9 20:52:29 CST 2021
|Release Version         |=> 5.10.60-amd64-desktop
|Machine ARCH            |=> x86_64
|CPU is                  |=> AMD Ryzen 7 3700X 8-Core Processor             
```
<br>
<br>
# how does this tool work? 
<br>
it works by taking various path's of the etc hosts file and loops irt back by connecting the domain name with the loopback 

# how can you add your own domains? 

this script opens a file called blacklist.txt in the file txt, when you want to add a website or blacklist one just open the file and type the domain name. an example is => www.twitter.com. now when you run the script the following will output 
<br>
<br>
# for this example i am on DEEPIN os using a pre compiled version of this script, with the following websites in the blacklist.txt

```
www.example.com
www.google.com
www.duckduckgo.com
www.blog.logrocket.com
www.liquidweb.com
www.apple.stackexchange.com
www.en.wikipedia.org
www.pkg.go.dev
www.twitter.com
www.facebook.com
```

# the following will output

```
 ______ _____ _______      ______  _____ 
 |  ____   |      |    ___ |  ____ |     |
 |_____| __|__    |        |_____| |_____|
-----------------------------------------------------------------------------


_________________________________________________
|System Name             |=> Linux
|Node/System Name        |=> X43DW91
|System Current Version  |=> #3 SMP Tue Nov 9 20:52:29 CST 2021
|Release Version         |=> 5.10.60-amd64-desktop
|Machine ARCH            |=> x86_64
|CPU is                  |=> AMD Ryzen 7 3700X 8-Core Processor             




 Script started blocking At:
_______________________________________
|Current Year        | 2021
|Current Month       | December
|Current Day         |  13
|Current Hour        | 14
|Current Minute      | 13
|Current Second      | 41
|Current Nanosecond  | 345331031
|____________________|__________________
 


  ______________HOSTS IN FILE__________________
 | 1 | www.example.com
 | 2 | www.google.com
 | 3 | www.duckduckgo.com
 | 4 | www.blog.logrocket.com
 | 5 | www.liquidweb.com
 | 6 | www.apple.stackexchange.com
 | 7 | www.en.wikipedia.org
 | 8 | www.pkg.go.dev
 | 9 | www.twitter.com
 | 10 | www.facebook.com
 | 11 | www.instagram.com
 
[ ? ] Connection was established? was host down or blocked?
 
[ * ] STAT: Trying TCP dialup again ->  &{{0xc000193880}}
                                                                                                                                                                                                                     
[ ? ] Connection was established? was host down or blocked?                                                                                                                                                          
                                                                                                                                                                                                                     
[ * ] STAT: Trying TCP dialup LAST TIME ->  &{{0xc000193b80}}                                                                                                                                                        
                                                                                                                                                                                                                     
[ ? ] Connection was established? was host down or blocked? ->  &{{0xc000134580}}                                                                                                                                    
                                                                                                                                                                                                                     
[ ? ] Connection was established? was host down or blocked?                                                                                                                                                          
                                                                                                                                                                                                                     
[ * ] STAT: Trying TCP dialup again ->  &{{0xc000134880}}                                                                                                                                                            
                                                                                                                                                                                                                     
[ ? ] Connection was established? was host down or blocked?                                                                                                                                                          
                                                                                                                                                            
[ * ] STAT: Trying TCP dialup LAST TIME ->  &{{0xc000134b80}}                  

```

# once the output continues you can now visit the website but you will recieve the following error 


![alt text](demo.png "Example")

