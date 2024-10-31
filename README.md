# binder_affinity
The goal of this project was to desing a protein that binds to EGFR. I limited my binder length to being between 50 and 150 sequences, due to constraints in the competiton that I'm entering. 
The following parameters were entered into RFDifusion to design a protien that binds to EGFR.

<img width="1274" alt="Screenshot 2024-10-31 at 10 25 19 AM" src="https://github.com/user-attachments/assets/143aa163-c5dd-4a4a-b7f1-165f5ccdd37f">


This is an image of the protein RFDiffusion designed binding to EGFR.
<img width="332" alt="Screenshot 2024-10-31 at 10 27 47 AM" src="https://github.com/user-attachments/assets/ce841d46-b540-4c61-94fd-22a1b98a9b22">

The results were downloaded and then imported into the binder_affinity code to compare it to other designed proteins. 

The output of the binder affinity code is below, with my protein's sequence ranking last. 

Ranking of Potential Binders:
1. SEEEEERERALKEIIEETRRELKAAKAKHGKVVVVLIMASSTLEPEFILELSKALIKEMKSLFPNVVLIIVVVGLAPASLLARIRDVSLELAKYAKSLGIKVIVIVGNENEAVFVPAFEALGVEVIVDRTIIEIAAEELGLSEEEVLARFAAAAELLDELFAADPSLRERYARLDVAGATELLLERLRELFGAKVERHERLITVEVERVLTPDERRRVTAILLTPEAAREVVERLVDLVVDLILEKIAEGHNVLVLVFTPTIALAREVAALFEERRPLLEEAGAAVIIRLVARDPDTFLI - MLM Loss: 6.843159993489583
2. LEEKKVCQGTSNKLTQLGTFEDHFLSLQRMFNNCEVVLGNLEITYVQRNYDLSFLKTIQEVAGYVLIALNTVERIPLENLQIIRGNMYYENSYALAVLSNYDANKTGLKELPMRNLQEILHGAVRFSNNPALCNVESIQWRDIVSSDFLSNMSMDFQNHLGSCQKCDPSCPNGSCW - MLM Loss: 8.65021832784017
3. GRPPKNVKVSGVDGNSATISFDLADENDKYILIMIGPANDPNSWTSWWLPHETSYLSISNLPPGAEYQVTFMMVRPGKMSPPITQDFKC - MLM Loss: 10.40660031636556
4. KPQRKTYYGNMKGREDYEPEQSKEVYAKKFASKTEEELEEVIKEEKAEIEKKKKQLEEDIKAGKVTEYNPKVKVITPVYPSEYKEVEE - MLM Loss: 10.430347124735514

It would appear that the longer the protein, the better the binding to EGFR is. This would make sense as the length of the protein sequence refelcts how complex the protein is, and thus how many bidning sites on EGFR it can target.
Since my protein is the shortest in sequence, it binds the worst. 
