# CodeFunDo++ 2019
Idea for CodeFunDo++ 2019
-------------------------------

### Blockchain Voting System

#### Current Systems 

* The current system uses Electronic Voting Machines (EVM). EVMs are set up in various polling booths across the country where people vote by pressing the button corresponding to the candidates. 
* Voting in India takes place at constituency level, where the people vote for candidates of various constituencies to join the Legislative Assembly. 
* People have to register for availing a Voter ID when they turn 18. After that based on the location of the person a voter list is generated and circulated across the corresponding polling booths. 
* On the day of voting, people have to reach the required polling booth and vote using the EVMs described above. 
  * In some places this voting is done using paper ballots instead of EVMs. 
* The result of the voting is released after counting the votes. 


#### Issues with the current system

* The major issue is that the EVMs are very suseptible to external interventions. Many cases of EVM hacking / rigging of EVM machines have been reported.
* Beyond just the issues with EVM machines, many a times citizens are not able to vote because they cannot make it to their own constituency. 
* There are also cases of names missing from the voting list.
* Another issue is the miscounting of votes that commonly happens when we use paper ballots. The task of counting and compiling is a very time consuming one and can be easily further improved. 
* Quite often voters are not aware of the full information of the candidates but are just coerced into voting for them by the other members of the party. 

### Our Solution 

#### What are we planning to build? 
 
* We plan to build a complete blockchain for voting that functions not only at the smaller district/constitency level but also at the national level. 
* Voters will be registered only at a national level rather and would be added to their constituencies.
* A voters list will not be created for the pooling booth as no voter will be assigned a particuar voting booth. 
  * Rather voters would vote for candidates of their constituencies without requiring to be present in a voting booth set up in that constituency. 
* The blockchain will be accompanied by a website that uses facial recognition and biometrics (as applicable) to verify the voters and provide the voters with the voting page. 
* The website would also furnish details of the participating candidates so that the voters may assure themselves of their choice. 
  * The details may include : 
    1. Metrics like - Promises made vs. Promises Kept, Attendance in the House
    2. Criminal Record
    3. Funds Utilization
  * This would also be paired with the Agenda set up the candidate.
  * The website would be dynamic to show the candidates belonging to the constitency of the voters.
* Each voter after voting would receive a reference ID so that they can later see that their vote was accounted for. 
* The counting would be done automatically at both the constituency level as well as the national level to ensure that there is no mishap.

#### How are we planning to build it?

* We plan to build an *Ethereum* based **private** blockchain that would be set up at all the voting booths across India. 
* There would be 2 blockchains running simultaneously: 
  * One at a constituency level
  * Other at a national level. 