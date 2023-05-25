## PPID: Strangers Sets: Preserving Drones' Location Privacy while Avoiding Invasions of Critical Infrastructures

## Formal verification with ProVerif
The security properties of `PPID` have been verified formally and experimentally by using the open-source tool <a href="https://prosecco.gforge.inria.fr/personal/bblanche/proverif/">ProVerif 2.04</a.

To verify the security of the proposed scheme, download the file <a href="ppid.pv">ppca.pv</a> and run: `./proverif ppid.pv | grep "RESULT"`.
To verify that the location is a strong secret (i.e., the attacker cannot launch offline guessing attacks on the location of the drone), please follow the guidelines inside the code.

<p align="center">
  <img src="./img/proverif.png" alt="PPCA" width="700">
</p>


## Developers
(^) Harshul Vaishnav        (harshul dot vaishnav at studenti dot unipd dot it)<br />
(^) Alessandro Brighente    (alessandro dot brighente at unipd dot it)<br />
(^) Mauro Conti             (mauro dot conti at unipd dot it)<br />
(-) Savio Sciancalepore    (s dot sciancalepore at tue dot nl)<br />

(^) University of Padova, Italy<br />
(-) Security Group - Faculty of Mathematics and Computer Science, Eindhoven University of Technology (TU/e), Eindhoven, The Netherlands<br />

## License
`PPCA` is released under the GNU General Public License v3.0 <a href="LICENSE">license</a>.
