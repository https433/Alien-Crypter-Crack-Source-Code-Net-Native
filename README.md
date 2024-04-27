<h1 align="center">Alien Crypter</h1>
<p align="center">

![image](https://user-images.githubusercontent.com/93733605/141330354-6cf4931e-64df-422a-90ed-43c8c5fc681b.png)



A crypter constitutes a variant of software adept at encrypting, obscuring, and manipulating malicious software, thus heightening its resistance against identification by security applications. Cyber malefactors employ this tool to fabricate malware capable of eluding security applications by assuming the guise of an innocuous program until its installation is accomplished. Diverse categories of crypters find existence.



              

<h2 align="center">Legal Notice</h2>
<p>
Crypter is designed exclusively for educational and investigative intentions. Its utility should be confined to systems or networks where you possess legitimate authorization. It must unequivocally not be employed for any unlawful or illicit endeavors. The author relinquishes any accountability for potential harm that might ensue from the utilization of the software found within this repository.
</p>
<p>
Upon compilation, Crypter SHALL employ encryption on the files residing within the computer on which its execution occurs. While Crypter furnishes the decryption key, granting access to decrypt encrypted files, it's plausible that glitches and other complications might potentially disrupt or thwart seamless decryption. As a result, an unrecoverable data loss is plausible. To preempt any plausible harm, <b>it is imperative to confine the use of Crypter to a dedicated test apparatus established for this explicit intent</b>.
</p>
<p>
Once more, <b>the author disclaims any accountability for prospective damages, and by obtaining this software, you validate and assent to this legal disclaimer.</b>
</p>

<h2 align="center">Operational Mechanism</h2>


### Constructor
The constructor serves as the tool that empowers you to personalize and forge the Crypter Ransomware. Several of the configurations you can define incorporate:

- Icon for the Executable Binary File
- Title/Heading for the Graphical User Interface (GUI)
- Font and Background Color for the GUI
- Bitcoin Wallet Address
- Ransom Fee
- Ransom Message
- Stipulated Time for Payment
- Eradication of File Shadow Copies
- File Types to Undergo Encryption

and an array of additional facets. Once these parameters are established, a mere press of the <b>BUILD</b> button suffices to engender the executable.


### Ransom Operation
Upon activation, Crypter shall undergo the ensuing sequence:

- Production of an AES-256 bit encryption/decryption key and its inscription into key.txt within the prevailing directory
- Quest for pertinent destinations (comprising network drives, user repositories, etc.) in pursuit of files that align
- Encryption of all located congruent files
- Presentation of the Crypter Graphical User Interface (GUI) to the afflicted party
    


