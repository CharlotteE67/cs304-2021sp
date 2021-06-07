# CS304 Review

## Lec01

​	Software processes:

<img src="CS304 Review.assets/image-20210605141706630.png" alt="image-20210605141706630" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605142737888.png" alt="image-20210605142737888" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605142833052.png" alt="image-20210605142833052" style="zoom:50%;" />



## Lec02

​		<img src="CS304 Review.assets/image-20210605143452316.png" alt="image-20210605143452316" style="zoom:50%;" />



### 		SVN: Apache Subversion

​			Create local copy: `svn checkout <address_to_remote> <name_of_local_dir>` `git checkout <branch_name>`

​			Commit local changes: `svn commit -m "msg"` `git commit -m "msg"`

​			Update local copy: `svn up` `git pull upstream master`

​			Telling svn/git about a new file to track: `svn add <file-name>` `git add <file-name>`

​			More commands:<img src="CS304 Review.assets/image-20210605144633951.png" alt="image-20210605144633951" style="zoom: 33%;" />

​			<img src="CS304 Review.assets/image-20210605144913163.png" alt="image-20210605144913163" style="zoom:50%;" />



​				Git: Distributed, checksum(first 7 chars). Modify->Stage->Commit

 <img src="CS304 Review.assets/image-20210605160457971.png" alt="image-20210605160457971" style="zoom:50%;" /> 

​				Building tool: make, ant, mvn, Gradle, ...

<img src="CS304 Review.assets/image-20210605164253969.png" alt="image-20210605164253969" style="zoom:50%;" />									<img src="CS304 Review.assets/image-20210605164524927.png" alt="image-20210605164524927" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605170546296.png" alt="image-20210605170546296" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605172639738.png" alt="image-20210605172639738" style="zoom:50%;" />

​		<img src="CS304 Review.assets/image-20210605173341465.png" alt="image-20210605173341465" style="zoom:50%;" />

## Lec03

<img src="CS304 Review.assets/image-20210605173646568.png" alt="image-20210605173646568" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605192359936.png" alt="image-20210605192359936" style="zoom:50%;" />

​			<img src="CS304 Review.assets/image-20210605201811453.png" alt="image-20210605201811453" style="zoom: 50%;" />

<img src="CS304 Review.assets/image-20210605202100323.png" alt="image-20210605202100323" style="zoom: 50%;" />

## Lec04

<img src="CS304 Review.assets/image-20210605211439699.png" alt="image-20210605211439699" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605214349637.png" alt="image-20210605214349637" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210605214908339.png" alt="image-20210605214908339" style="zoom:50%;" />

![image-20210606021353443](CS304 Review.assets/image-20210606021353443.png)

![image-20210606021420550](CS304 Review.assets/image-20210606021420550.png)

![image-20210606021614041](CS304 Review.assets/image-20210606021614041.png)

![image-20210606024425658](CS304 Review.assets/image-20210606024425658.png)

![image-20210606024641001](CS304 Review.assets/image-20210606024641001.png)

![image-20210606024922476](CS304 Review.assets/image-20210606024922476.png)

## Lec05

​		Each test should be independent of each other

​		Any given behavior should be specified in one and only one test.

​		`assertEquals(expected, actual)`

<img src="CS304 Review.assets/image-20210606025249451.png" alt="image-20210606025249451" style="zoom: 67%;" />

<img src="CS304 Review.assets/image-20210606025505823.png" alt="image-20210606025505823" style="zoom: 67%;" />



​			Code coverage:

<img src="CS304 Review.assets/image-20210606030151571.png" alt="image-20210606030151571" style="zoom: 67%;" />

<img src="CS304 Review.assets/image-20210606030410169.png" alt="image-20210606030410169" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606030431572.png" alt="image-20210606030431572" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606113622247.png" alt="image-20210606113622247" style="zoom: 80%;" />

Jacoco:`java -jar- -javaagent:/jacocoagent.jar=destfile=/jacoco.exec`

EvoSuite: EvoSuite uses evolutionary algorithm to generate and optimize whole test suites towards satisfying a coverage criterion.



## Lec06

​	<img src="CS304 Review.assets/image-20210606033416221.png" alt="image-20210606033416221" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606033743459.png" alt="image-20210606033743459" style="zoom: 67%;" />

<img src="CS304 Review.assets/image-20210606033757474.png" alt="image-20210606033757474" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606113313194.png" alt="image-20210606113313194" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606113850106.png" alt="image-20210606113850106" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606114234298.png" alt="image-20210606114234298" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606132303404.png" alt="image-20210606132303404" style="zoom:67%;" />

![image-20210606132349202](CS304 Review.assets/image-20210606132349202.png)

![image-20210606132504272](CS304 Review.assets/image-20210606132504272.png)

![image-20210606132737195](CS304 Review.assets/image-20210606132737195.png)



## Lec07

![image-20210606132930120](CS304 Review.assets/image-20210606132930120.png)

![image-20210606135101870](CS304 Review.assets/image-20210606135101870.png)

Reverse Engineering

![image-20210606135407743](CS304 Review.assets/image-20210606135407743.png)

![image-20210606135722079](CS304 Review.assets/image-20210606135722079.png)

## Lec09

<img src="CS304 Review.assets/image-20210606140844152.png" alt="image-20210606140844152" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606142121216.png" alt="image-20210606142121216" style="zoom:67%;" />



### Testing: 

- Dynamic analysis(Astor, PraPR)

- static analysis(no dynamic execution, detect possible defects in an early stage). 

  - Checkstyle: focus on java coding style and standards.<img src="CS304 Review.assets/image-20210606142617689.png" alt="image-20210606142617689" style="zoom:50%;" />

  - PMD: scan source code and looks for potential problems<img src="CS304 Review.assets/image-20210606142841458.png" alt="image-20210606142841458" style="zoom:50%;" />

    <img src="CS304 Review.assets/image-20210606143501410.png" alt="image-20210606143501410" style="zoom:67%;" />

  - Findbugs  <img src="CS304 Review.assets/image-20210606144348728.png" alt="image-20210606144348728" style="zoom:67%;" />

  - Defensive Programming: no warning by Static Analysis



## Lec10

​	Tools check for coding standard: PIT, CheckStyle, FindBugs, PMD

<img src="CS304 Review.assets/image-20210606145049272.png" alt="image-20210606145049272" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606160818613.png" alt="image-20210606160818613" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606161316423.png" alt="image-20210606161316423" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606161336117.png" alt="image-20210606161336117" style="zoom: 50%;" />

<img src="CS304 Review.assets/image-20210606162016210.png" alt="image-20210606162016210" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606162156001.png" alt="image-20210606162156001" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606162441607.png" alt="image-20210606162441607" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606162606970.png" alt="image-20210606162606970" style="zoom:50%;" />

```java
/**
* This is where the text starts. The asterisk lines 
* up with the first asterisk above; there is a space 
* after each asterisk. The first sentence is the most 
* important: it becomes the “summary.” 
*
* @param x Describe the first parameter (don’t say its type). 
* @param y Describe the first parameter (don’t say its type). 
* @return Tell what value is being returned (don’t say its type). 
*/ 
public String myMethod(int x, int y) { // p lines up with the / in /**

/*
@auther 
@version
*/
    //TODO //FIXME //XXX
```

<img src="CS304 Review.assets/image-20210606162903670.png" alt="image-20210606162903670" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606164143079.png" alt="image-20210606164143079" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606164200330.png" alt="image-20210606164200330" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606165223053.png" alt="image-20210606165223053" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606165512509.png" alt="image-20210606165512509" style="zoom:50%;" />

## Lec11

<img src="CS304 Review.assets/image-20210606172252842.png" alt="image-20210606172252842" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606172310471.png" alt="image-20210606172310471" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606172401719.png" alt="image-20210606172401719" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606172710282.png" alt="image-20210606172710282" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606172725702.png" alt="image-20210606172725702" style="zoom:50%;" />

## Lec12

<img src="CS304 Review.assets/image-20210606173236705.png" alt="image-20210606173236705" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606173730431.png" alt="image-20210606173730431" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606174042042.png" alt="image-20210606174042042" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606174647900.png" alt="image-20210606174647900" style="zoom:67%;" />

<img src="CS304 Review.assets/image-20210606174950968.png" alt="image-20210606174950968" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175017201.png" alt="image-20210606175017201" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175032393.png" alt="image-20210606175032393" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175044579.png" alt="image-20210606175044579" style="zoom:50%;" /><img src="CS304 Review.assets/image-20210606175059339.png" alt="image-20210606175059339" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175123086.png" alt="image-20210606175123086" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175147890.png" alt="image-20210606175147890" style="zoom:50%;" />



## Lec13

<img src="CS304 Review.assets/image-20210606175435448.png" alt="image-20210606175435448" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606175621441.png" alt="image-20210606175621441" style="zoom:50%;" />

CI Server:

 <img src="CS304 Review.assets/image-20210606175957895.png" alt="image-20210606175957895" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606180716208.png" alt="image-20210606180716208" style="zoom: 33%;" />

Big-Bang Integration Testing, Incremental Integration Testing, Top-Down Integration, Bottom-Up Integration, "Sandwich" Integration

<img src="CS304 Review.assets/image-20210606182147502.png" alt="image-20210606182147502" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606190347454.png" alt="image-20210606190347454" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606190414972.png" alt="image-20210606190414972" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606190443091.png" alt="image-20210606190443091" style="zoom:50%;" />



## Lec14

<img src="CS304 Review.assets/image-20210606194330149.png" alt="image-20210606194330149" style="zoom:50%;" />



<img src="CS304 Review.assets/image-20210606194109865.png" alt="image-20210606194109865" style="zoom:50%;" />

<img src="CS304 Review.assets/image-20210606214856565.png" alt="image-20210606214856565" style="zoom:50%;" />



## Appendix

Extreme Programming(XP)		

Software configuration management (SCM) 

Version Control System(VCS)

Test Driven Development(TDD)

Weighted Methods Per Class (WMC)

Depth of Inheritance Tree (DIT) 

Number of Children (NOC)

Coupling between Object Classes (CBO)

Response for a Class (RFC)

Lack of Cohesion in Methods (LCOM)

Component-Based Software Engineering(CBSE)

Commercial Off-the-Shelf Software (COTS) 

Experience Improvement Program (CEIP) 

Continuous Integration(CI)

Continuous Delivery(CD)

Regression Test Selection(RTS)

Automated Program Repair (APR)
