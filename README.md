Pokereum
========
Ethereum using Telehash RTC, cryptography and smart contract technology to provide a secure, efficient, provably fair and decentralized global poker. This repository is a largely a resource for documentation and ponter to other relevant components http://www.pokereum.io 


### Table of Contents

* [Whitepaper](#Whitepaper)
* [Demo](#Demo)
* [Routing](#Routing)
* [Pokereum RTC Multi-Party Computation](#Pokereum-RTC)
* [Security & Data Athentication](#SecurityDataAthentication)    
* [Shadow Poker](Shadow-Poker)
* [Network](#Network)
* [Client Downloads](#Downloads)
* [Wiki](#wiki)
* [Tests](#Tests)
* [Tech Stack](#Tech-Stack)







#<a name="whitepaper"></a>     
##Whitepaper    

Under peer review here :: https://github.com/Pokereum/pokereum/wiki/Whitepaper           



Only a few components parts provided here most of the code base is hosted on a private repo here : https://bitbucket.org/innovator256/pokereum    

-  
-  
      
      

#<a name="Demo"></a>   
##Demo
Preview implementation : [P2p UX Demo:]( https://www.youtube.com/watch?v=ydqsLi2CAgQ)      



-  
-     



#<a name="Routing"></a>
##Routing      
Routing library usinggraceful degradation for the most efficient available transport for signaling node for uplinking on the pokereum Network    

Routing Library : [Pokereum-Telehash-Router](https://github.com/Pokereum/Pokereum-Telehash-Router)






-  
-     
      
      



#<a name="Pokereum-RTC"></a>                
##Pokereum RTC Multi-Party Computation    
Multi-Party-Computation-RTC represents "poc 1" of the Pokereum real time game state synchrony and private computation between poker nodes on the pokereum network. Note there is no actual security in this version; i.e state signing, private encryption and authentication which is partially accomplished with integration of the Shadow Poker protocol     

[Pokereum-Multi-Party-Computation-RTC](https://github.com/Pokereum/Pokereum-Multi-Party-Computation-RTC)



-  
-      
      
     
       
       
#<a name="SecurityDataAthentication"></a>                 
##Security and Data Athentication             



-  
-  
      
      

 
 
 
 

#<a name="Shadow-Poker"></a>     
##Shadow Poker          
        



-  
-  
      
    
#<a name="Network"></a>    
##Network                   



-  
-  
      
      
     
#<a name="Downloads"></a>    
##Client Downloads             
     


-  
-  
      
      


#<a name="wiki"></a>     
##wiki         




-  
-  
      
      
#<a name="Tests"></a>      
##Tests           
   


-  
-  
      
      


#<a name="Tech-Stack"></a>     
##Tech Stack           
- Electron <br/>
- Nodejs<br/>
- jQuery<br/>
- html5 framework: phaserjs<br/>
- Telehash // Nat hole punching and routing via UDP and RTC<br/>
- Ethereum whisper/IPFS<br/>
- Ethereum solidity<br/>
- Hashing, encryption, secret sharing
