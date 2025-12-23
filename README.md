# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**

<img width="278" height="92" alt="image" src="https://github.com/user-attachments/assets/d4682bcf-eeec-491f-a161-50eab672c724" />

**To measure RTh or RN**


<img width="243" height="80" alt="image" src="https://github.com/user-attachments/assets/6d35f8c1-1a5e-4243-acfc-6401827beddf" />


**To measure IN or Isc**

<img width="298" height="78" alt="image" src="https://github.com/user-attachments/assets/0a0e1342-1480-4173-91b6-a160102108a8" />


**Norton’s equivalent circuit**

<img width="202" height="127" alt="image" src="https://github.com/user-attachments/assets/34cd4337-8f51-4c88-ba54-5b58d4f2943e" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L

<img width="247" height="153" alt="image" src="https://github.com/user-attachments/assets/252f7bce-a94e-4975-8f9d-696b12f3c11b" />

**TABULAR COLUMN:2**

To measure RTh or RN

<img width="212" height="135" alt="image" src="https://github.com/user-attachments/assets/204c4945-d86e-4ddd-af87-a74a8798f061" />



**TABULAR COLUMN:3**

To measure IN or Isc

<img width="256" height="111" alt="image" src="https://github.com/user-attachments/assets/025fe5d3-23ed-4de8-b689-128b0c5c341e" />

	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

<img width="253" height="161" alt="image" src="https://github.com/user-attachments/assets/066a2711-c435-4e35-b8f4-57e3777ff774" />


**Verification of Norton’s theorem**

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 
<img width="312" height="542" alt="image" src="https://github.com/user-attachments/assets/c4d6d3c2-8a6e-4c5f-b159-fc2ab83f198f" />


<img width="207" height="181" alt="image" src="https://github.com/user-attachments/assets/e662ace4-aa98-4996-ad1c-3de05bef8e80" />




<img width="337" height="397" alt="image" src="https://github.com/user-attachments/assets/4a677199-1a28-4497-bf8a-651e1bf2e911" />


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
