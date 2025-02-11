########################################## HD/Network ##########################################<br><br><br>
- Drag the correct definition aside the corresponding features <br>
Preventing unauthorized access to a network     Cyber<br>
Collecting evidences to prove what has happened   Digital<br>
Reconstruct a specific incident   Digital<br>
Avoiding misuse of a computing facility  Cyber<br>
Monitoring the working state of a computing facility Cyber <br>
Performing offline analysis of a digital evidence Digital<br>
Taking care of the acquisition, storage, and the validation of digital evidences Digital<br>

- Considering acquisition and collection operations, reorder the following operations from the most to the least critical one (i.e., putting first those where the loss of data is highly-probable).<br>
[Collection of switched‑on devices]<br>
[Acquisition of a switched‑on device]<br>
[Collection of switched‑off devices]<br>
[Acquisition of a switched‑off device]<br>

- In a collection process, place the following operations in chronological order.<br>
[Check if there are volatile data]<br>
[Perform live acquisition]<br>
[Check if the data are stable]<br>
[Standard switch‑off]<br>
[Unplug, collect cables]<br>

- Given the following properties of a hash function h(f):file→{0,1}n<br>
Resilience to pre-image → Given a digest d, finding a string such that h(f)=d is computationally-unfeasible<br>
Resilience to second pre-image → Given d_1=h(f_1), it is computationally-unfeasible to find f_2 s.t. h(f_2)=d.<br>
Resilience to collision → Looking for f_1 and f_2 s.t. h(f_1)=h(f_2) is computationally-unfeasible<br>

- Associate the correct digest length to each hashing algorithm<br>
SHA-256 → 256 bits<br>
SHA-1 → 160 bits<br>
MD5 → 128 bits<br>

- In the acquisition and handling processes of a digital evidence (DE), we must ensure the  pertinence, the reliability, adequateness, verificability, reproducibility of the tools and operations that we adopted. Assign each explanation to the most suitable feature.<br>
DEFR and DES can justify their choices → Verificability<br>
The chain of operation can be reconstructed and re-applied → Reproducibility<br>
The Digital Evidence First Responder must select the best acquisition tools and strategies → Adequateness<br>
The DE must be relevant to the incident (proved in the documentation) → Pertinence<br>
The authenticity of the DE (no alteration) must be granted and proved → Reliability<br>

- Among the following fields, choose the ones that can be included within digital forensics<br>
  [X] multimedia forensics<br>
  [X] mobile forensics<br>
  [X] cloud forensics<br>
  [X] disk forensics<br>
  [ ] forensic genomics<br>

- Among the following statements concerning the Chain-of-Custody characteristics and procedures, select those that are TRUE.<br>
  [ ] it must keep a log file of the acquisition and the accesses<br>
  [X] It must report when, where, who and why the evidence was accessed<br>
  [ ] the evidence must be available to everyone<br>
  [X] The evidence must be identified by an ID<br>
  [X] it must document and justify possible alterations<br>

- Please select , among the following standards, the one that defines the guidelines for the identification, acquisition and the preservation of digital evidences.<br>
  [ ] ISO/IEC 27041<br>
  [X] ISO IEC 27037/2012<br>
  [ ] ISO/IEC 17025:2005<br>

- Given the following tasks:<br>
    Check the area involved in the incident<br>
    Profile the persons that access the area and keep people away from devices<br>
    Avoid changing the state of devices<br>
    Document the scene, components, cables (pictures, video, drawings),<br>

which of the following roles must take care of them<br>
  [X] Digital Evidence First Responder<br>
  [ ] Forensic Laboratory Operator<br>
  [ ] Digital Evidence Specialist<br>
  [ ] Incident Response Analyst<br>

- Which of the following phases are defined within the ISO IEC 27037/2012 standard<br>
  [X] Acquisition<br>
  [X] Seizure<br>
  [ ] Incrimination.<br>
  [X] Identification<br>
  [ ] Documentation<br>
  [X] Preservation<br>

- Select which of the following statements concerning the Digital Evidence First Responder (DEFR) and the Digital Evidence Specialist (DES) are TRUE.<br>
  [X] DEFR operates first on the crime scene<br>
  [X] DES can operate as a DEFR<br>
  [ ] DES can never perform an acquisition of a digital evidence<br>
  [ ] DEFR can deal with a wide range of different technical issues<br>

- A NIDS monitoring the network can generate three possible outcomes: <br>
    S: the network is safe<br>
    F: network is not working correctly (overloaded)<br>
    A: there is an attack going on.<br>
Assign the correct tables of mass values to each statement.<br>
"90% of the sensed measurements suggest the network is safe."<br>
[m(S)=0.9; m(S,A,F)=0.1]<br>
"30% of evidences shows that the network is either under attack or malfunctioning; there is also another 30% of measurements suggesting an attack"<br>
[m(A)=0.3; m(A,F)=0.3; m(A,F,S)=0.4]<br>
"Something strange is happening, but 70% of evidences prove that no attack is going on"<br>
[m(S,F)=0.7; m(S,F,A)=0.3]<br>
"70% of evidences suggest that the network is safe; 10% show a malfunctioning"<br>
[m(S)=0.7; m(F)=0.1; m(S,F,A)=0.2]<br>

- Assign each [belief,plausibility] couple to the correct statement.<br>
[1,1] → I am sure that the hypothesis is true.,<br>
[0,1] → I can not conclude anything on the hypothesis,<br>
[0.3,0.7] → the hypothesis is not totally possible,<br>
[0.75,0.9] → Although not completely plausible, there is a strong belief that the hypothesis is true.<br>

- In network forensics, data collection can be performed using a "Stop, look, and listen" or a "Catch-it-as-you-can" strategy. Concerning the former, select which of the following statements are appropriate.<br>
  [X] It performs a real-time processing<br>
  [ ] It requires much larger memory storage than a "Catch-it-as-you-can" strategy<br>
  [X] it requires fast processing<br>
  [ ] All the listened packets are stored<br>
  [X] Only certain packets are stored<br>

- In relation to Ethernet forensics, select the following TRUE statements.<br>
  [ ] MAC flooding force switches into the promiscuous mode<br>
  [ ] No. it is the failopen mode, where all the packets are forwarded (like in shared ethernet)<br>
  [ ] Sniffing packets in a switched ethernet can be performed whenever the network card is set in promiscuous mode.<br>
  [X] Sniffing packets can be performed using an ARP spoofing strategy<br>
  [ ] It is necessary to alter the ARP table.<br>

- Which of the following methods can be used to detect whether on a machine there is a sniffer running?<br>
  [ ] Sending a broadcast ARP with a wrong MAC/IP pairing<br>
  [ ] Check the ping latency<br>
  [ ] Sending a ping to the suspected machine with a wrong MAC address<br>
  [X] Check for duplicates in the ARP table of a machine.<br>

- Select among the following, some sniffing tools or softwares<br>
  [ ] Ethereal<br>
  [ ] Snort<br>
  [X] Wireshark<br>
  [ ] ARP watch<br>
  [ ] Neped<br>
  [X] Ettercap<br>

- Among the following, select the antisniffing softwares or strategies<br>
  [X] Add some MAC address permanently in tables<br>
  [ ] Flooding the network<br>
  [X] Snort<br>
  [ ] Wireshark<br>
  [X] Cyphering the data (PGP, SSH)<br>

- Select which of the following operations must be performed in router forensic analysis.<br>
  [ ] ping the router<br>
  [X] review routing tables<br>
  [ ] switch the router off<br>
  [X] record system time and logged users<br>
  [X] view ARP cache looking for evidence of IP and MAC spoofing<br>

- Select which of the following softwares and tools can be used to carry on a Man-In-The-Middle attack on a router<br>
  [ ] Encryption<br>
  [X] VIPPR<br>
  [ ] Ultima Ratio<br>
  [ ] Router Audit Tool (RAT)<br>

- Which of the following incidents a DEFR could analyze on a router<br>
  [X] The working state of the router is compromised (DoS)<br>
  [ ] The router is working in promiscuos mode<br>
  [X] The routing table has been manipulated<br>
  [ ] Theft of Information<br>
  [ ] The router is infected by a malware performing SYN flood attacks<br>

- Network-based Intrusion Detection Systems (NIDS) ...  (select the most appropriate sentences)<br>
  [ ] ... tell if the attack is successful.<br>
  [ ] ... evaluate network traffic.<br>
  [X] ... raises an alarm during some suspicious network activity.<br>
  [ ] ... monitor a specific protocol.<br>

- Among the following, select the most correct statements concerning Host-based IDS.<br>
  [ ] HIDS can detect out-of-band attacks (e.g., juice jacking)<br>
  [ ] Maintenance for different HIDS is extremely easy.<br>
  [ ] HIDS are robust to fragmentation and TTL attack.<br>
  [ ] HIDS provide a network-wide overview of the attack<br>
  [X] HIDS can monitor log files, system activities, errors<br>

- Concerning Network-based Intrusion Detection Systems (NIDS), we can state that ...<br>
  [X] ... they do not waste network or CPU resources<br>
  [ ] ... they are robust to packet fragmentation and re-assembly<br>
  [ ] ... they are not affected by TTL attacks<br>
  [X] ... they can experience some problems if the network usage increases.<br>
  [X] ... they work in promiscuous mode.<br>

- In signature-based IDS trigger, ...<br>
  [ ] ... attackers can not pre-configure an IDS-transparent attack.<br>
  [X] ... it is possible to detect a previously-known attack only.<br>
  [ ] ... profiles are dynamic.<br>
  [X] ... protection is instantaneous after signature update.<br>

- According to Dempster-Schafer theory, the belief associated to a given evidences or hypothesis ...<br>
  [X] ... is always lower than the plausibility.<br>
  [X] ... characterizes how much the evidence/hypothesis is provable.<br>
  [ ] ... it correspond to 1 minus the plausibility of that evidence/hypothesis<br>
  [ ] ... can be higher than probability.<br>

- Given the two IDS W1,W2 with mass values<br>
  [X] W1 excludes there is an attack.<br>
  [ ] Combining the evidences of the two sensors, the network monitor concludes there is an attack.<br>
  [ ] The opinion of the most uncertain IDS prevails<br>
  [X] Combining the evidences of the two sensors, the network monitor concludes there is a network failure.<br>

- Given three IDS whose evidence results can be combined using DS theory, we can state that ...<br>
  [X] ... you must have a mass entry for each non-null intersection<br>
  [ ] ... order of binary combination does not matter.<br>
  [ ] ... you must have a mass entry also for null intersections<br>

########################################## Multimedia and Social##########################################<br><br><br>
- Which of the following elements is one of critical issues in forensic analysis of IoT devices?<br>
  [X] Lack of training for DEFR<br>
  [ ] Devices are easily identifiable.<br>
  [ ] Availability of metadata<br>
  [ ] Data stability<br>

- Which of the following traces is not usually used in social media forensics?<br>
  [ ] Times of activity<br>
  [X] Packet streams<br>
  [ ] Communications pattern<br>
  [ ] The social footprint<br>

- Which of the following traces can not be used to detect a deepfake image or video?<br>
  [X] EXIF values<br>
  [ ] Facial moles<br>
  [ ] Blinking<br>
  [ ] Glares<br>

- In detecting a forged image, which of the following inconsistencies are not going to be checked?<br>
  [ ] PRNU inconsistencies<br>
  [ ] Geometric inconsistencies<br>
  [ ] Illumination inconsistencies<br>
  [X] All of the other ones.<br>


- In writing a forensic legal report, state which of the following sections comes at first place.<br>
  [ ] CV<br>
  [ ] List of appendixes<br>
  [X] Summary of conclusions<br>
  [ ] Analysis<br>

- An audio forensic analysis is analyzing the different replicas of the same sound recorded in the audio file; in this activity, he is ... (select the correct answer)<br>
  [ ] ... transcripting the events.<br>
  [ ] ... classifying the events in the scene (footsteps, voices).<br>
  [ ] ... looking for the Electrical Network Frequency (ENF).<br>
  [X] ... localizing the audio by estimating the room reverberation.<br>

- In ENF analysis, a forensic experts operating in Italy is  ... (choose the correct answer)<br>
  [ ] ... selecting different harmonics of the nominal frequency f0=60<br>
  [X] ... selecting different harmonics of the nominal frequency f0=50<br>
  [ ] ... averaging results of different locations.<br>
  [ ] ... computing Mel Cepstrum Transform Coefficients.<br>

- Among the following images, select the one that proves to be the most appropriate in order to estimate the PRNU<br>
 [X] The white one<br>

- Given an image I under examination and the PRNU pattern K^ (associated to a camera), select the most appropriate operation to verify that the image I has been taken with the camera associated to K^<br>
  [X] Compute the correlation between K^ I and W^, where W^ is the residual obtained by denoising I<br>
  [ ] Compute the correlation between I and W^, where W^ is the residual obtained by denoising I<br>
  [ ] Compute the correlation between K^ and W^, where W^ is the residual obtained by denoising I<br>
  [ ] Compute the correlation between I and K^<br>

- Concerning the Photo Response Non Uniformity (PRNU) noise, we can state that (select the correct ones):<br>
  [X] it is generated by artifacts in the fabrication process of the sensor matrix.<br>
  [X] it generates a multiplicative noise components depending on light intensity<br>
  [ ] it is robust to compression and most editing steps<br>
  [ ] it can be easily estimated from a highly texture image<br>
  [ ] it depends on temperature<br>

- An imaging sensor matrix is made of CCD units. Concerning each unit, we can state (select the correct ones):<br>
  [X] charges are transferred using a shift register circuitry<br>
  [ ] reading is sequential<br>
  [X] the first capacitor is charged according to light intensity<br>

- Concerning CMOS imaging sensors, we can state that (select the correct ones):<br>
  [ ] they can be activated because of a blooming effect<br>
  [ ] they are made of 3 transistors<br>
  [X] dedicated circuitry is used to control the reading<br>
  [X] values are sequentially read according to a row-column ordering<br>
  [ ] they are based on a shift register circuitry<br>

- Given the following image select the most appropriate statements among the following.<br>
  [ ] The radial distortion coefficient k_1 is lower than 0<br>
  [X] The radial distortion coefficient k_1 is higher than 0<br>
  [ ] Barrel radial distortion is present<br>
  [X] Pincushion radial distortion is present<br>

- Select the correct sentences about chromatic aberration among the following ones:<br>
  [X] It depends on light refraction passing from air to lens material and viceversa<br>
  [ ] It is more evident on the center of the lens<br>
  [X] It can be compensated by an additional lens<br>
  [X] It is due to the fact that the lens makes different wavelengths converge to different points.<br>

- Which among the following processing steps are usually adopted in a video codec?<br>
  [X] quantization<br>
  [ ] psycho-acoustic models<br>
  [X] transform-coding<br>
  [ ] subband decomposition<br>
  [X] motion prediction<br>

- Assuming that you want to improve the clarity and visibility of a face in a frame from a video surveillance sequence taken at night by a low resolution camera, what operation would you consider ... (among the following)<br>
 [X] magnification<br>
 [X] frame integration<br>
 [X] gamma correction<br>
 [ ] blurring compensation<br>
 [ ] motion ehnancement<br>
 [X] noise reduction<br>

- Concerning a recaptured video using a handheld device, select the wrong statement about motion cues<br>
  [X] motion cues are highly uncorrelated.<br>
  [ ] motion cues are highly correlated<br>
  [ ] motion cues are computed from local feature points<br>

- Considering a video re-capture, select the correct statement among the following:<br>
  [ ] Recapture produces blocking artifacts on the acquired image.<br>
  [X] Ghosting artifacts are present.<br>
  [ ] Ghosting artifacts can be modelled as a non-linear operation<br>
  [ ] Artifacts are never periodic<br>

- Assign to each statement the corresponding type of watermarking algorithm.<br>
It is less intuitive and difficult to analyze [X] Quantization-based<br>
It follows a strategy similar to CDMA in communications [X] Additive spread-spectrum<br>
It combines two simpler watermarking strategies [X] Spread-Transform Dither Modulation<br>

- Assign the proper definition/description to each concept.<br>
In attacks [X] The hidden info is supposed to be erased<br>
In watermarkig [X] the hidden info is supposed to be detectable<br>
In steganography [X] the hidden info is supposed to be detectable only for certain user<br>


- Complete the following sentences concerning the relation between forensic and antiforensic strategies.<br>
Antiforensic strategies want to<br>
  [X] Cancel processing footprint...<br>
Forensic analysts<br>
  [X] look for processing ....<br>
Non-reversible processing operations<br>
  [X] leave (unintentionally)...<br>

- Performances of a watermarking strategy can be measured using<br>
  [X] ROC<br>
, while the performance of a data hiding strategy must be measured using<br>
  [X] BER<br>
. In both strategies it is possible to take into account<br>
  [X] PSNR<br>
(or other quality measurements) and<br>
  [X] bitrate<br>
to evaluate the impact of each approach on the rate-distortion performance.<br>

- Given the following statements, assign the strategy (watermarking/cryptography) that fits the definition most.<br>
It does not prevent from making untraceable copies     Crypto<br>
It allows a free distribution of the image/video content     Watermarking<br>
It is unperceptible     Watermarking<br>
it prevents unauthorized users from accessing the multimedia content Crypto<br>
it can be applied multiple times without compromising the accessibility of the content   Watermarking<br>


- Classify the following strategies into passive and active ones.<br>
Watermarking      Active<br>
CFA estimation    Passive<br>
Steganography      Active<br>
PRNU estimation    Passive<br>
Leveraging compression traces  Passive<br>
Encryption  Active<br>
Checking inconsistencies Passive<br>

- Reorder in the correct sequence the following operations of the JPEG processing chain.<br>
1) Color conversion<br>
2) Block partitioning<br>
3) DCT<br>
4) Quantization<br>
5) Entropy coding<br>

- Given the following JPEG images, assign the correct quality factor to each one.
  [X] Better Quality means higher QF....

  
########################################## Anomaly detection and GANs##########################################<br><br><br>
- Among the following, select the wrong statement about the Frechet Inception Distance or FID.<br>
  [X] It is not affected by visual artifacts<br>
  [ ] It models real and fake data as a multivariate distributions.<br>
  [ ] It is robust to noise<br>
  [ ] It can be computed using mean and covariance matrix for fake and real data only.<br>

- The metric Inception Score (IS) will provide a high values for GANs that .... (select the correct statement)<br>
  [ ] generate p(y) with a low entropy.<br>
  [ ] generate realistic data x<br>
  [X] aim at making p(y) as uniform as possible.<br>
  [ ] aim at making p(y|x) as uniform as possible.<br>

- Which of the following loss function can lead to a vanishing gradient problem in a GAN?<br>
  [ ] L(D,G)=D(x)−D(G(z))<br>
  [ ] L(D,G)=−0.5Ez[logD(G(z))]<br>
  [X] L(D,G)=Ex[logD(x)]+Ez[log(1−D(G(z)))]<br>

- Which of the following attack types are most likely adressing an IDS?<br>
  [X] Evasion attack<br>
  [ ] Poisoning attack<br>
  [ ] Model extraction<br>

- In clean data learning for anomaly detection, we can NOT use the training set to create ...<br>
  [ ] Recurrent Neural Networks<br>
  [X] A multiclass SVM classifier<br>
  [ ] A dynamical system from Partial Differential Equations<br>
  [ ] ARMA models<br>

- Conserning an isolation forest algorithm, select the wrong statement among the following:<br>
  [ ] Node splitting is repeated until every input points is located on a leaf.<br>
  [ ] For each tree, the attribute selection order is random.<br>
  [X] Anomalies usually place at the lowest average depth for the trees<br>
  [ ] Classification is performed computing the average depth for a given input samples.<br>

- Which of the following classification strategies is  suitable for anomaly detection.<br>
  [ ] Few shots learning networks<br>
  [ ] Isolation forest<br>
  [ ] None of the mentioned strategies<br>
  [X] All of the mentioned strategies<br>
  [ ] One-class SVM<br>

- Which of the following metrics is used to create a ROC (receiver operative characteristics) curve?<br>
  [ ] Precision<br>
  [ ] Accuracy<br>
  [X] Recall<br>
  [ ] F1 score<br>

- Considering a sudden decrease of temperature in July (Northern emisphere), we can state that it is a ....<br>
  [ ] Collective anomaly<br>
  [X] Contextual anomaly<br>
  [ ] Point anomaly<br>

- Which among the following ones is NOT an anomaly type.<br>
  [ ] Collective anomaly<br>
  [X] Systematic anomaly<br>
  [ ] Point anomaly<br>
  [ ] Contextual anomaly<br>

- Which among the following conditions makes the WDAD (Well-Defined Anomaly Distribution) assumption NOT valid<br>
  [ ] Impossibility of using deep learning for anomaly detection<br>
  [X] Adversarial conditions<br>
  [ ] Unknown anomaly<br>


##########################################Biometric traces##########################################<br><br><br>

- Select the wrong statement concerning the M82 algorithm:<br>
  [ ] The list of matching minutiae pairs is ordered according to their weights. <br>
  [ ] A weight is assigned to each matching pair. <br>
  [X] A coarse pre-alignment is performed using the Top 2 matching pair. <br>
  [ ] Small deformation can be compensated by a tensor transformation. <br>

- Given the following set of biometric scheme, select the one which is not processing bilevel signals.<br>
  [ ] Fingerprint identification.<br>
  [ ] Vision-based gait analysis.<br>
  [ ] DNA sequence matching (in Voss representation).<br>
  [X] Face recognition.<br>

- Among the following sets of biometric measures, select the one where all the metric do not use Gabor filters in their processing pipeline.<br>
  [ ] Iris and voice recognition.<br>
  [ ] Fingerprint and face recognition.<br>
  [X] Gait analysis and voice recognition.<br>
  [ ] Fingerprint and iris imaging.<br>

- Considering the scaling factor computation in a refinement of fingerprint alignment (described by the parameter s in the following image) Select the wrong statement among the following ones.<br>
  [ ] The parameter s corresponds to the ratio between the length of mi1,mi2 and the length mj1,mj2<br>
  [ ] The final set of parameters is Δx,Δy,θ,s<br>
  [X] Minutiae  mi1,mj1 belong to the same fingerprint.<br>
  [ ] Parameters are optimized using an iterative procedure.<br>

- Considering Hough transform to fit one  line to a set of points, select the false statement among the following ones:<br>
  [ ] Complexity depends on parameter quantization.<br>
  [ ] Each line is a point in a 2D parameter space.<br>
  [X] Parametrization xcosθ+ysinθ=ρ is less accurate than using slope and intercept.<br>
  [ ] Hough transform allows to identify more fitting lines.<br>

- Considering the similarity score for fingerprint matching, select the wrong statement among the followings.<br>
  [ ] It is possible to weight the matching according to minutia quality.<br>
  [ ] It is possible to consider the intersection of minutiae set.<br>
  [X] Pairing identifies the exact matching between couples of minutiae.<br>
  [ ] The standard similarity score is the ratio between the matching minutiae and the average number of minutiae between query and template fingerprints.<br>

- Considering fingerprint descriptors used in fingerprint indexing, please select the wrong statement among the following.<br>
  [X] Geomtric propetries are usually defined by arrays of 4 values.<br>
  [ ] Triangle information is stored in a hash table.<br>
  [ ] Number of ridges between couples of minutiae could be used.<br>
  [ ] Length of triangle sides could be considered.<br>

- Considering the equation argmaxW|WTSW| select among the following sentences the wrong one.<br>
  [X] The equation computes an LDA decomposition for face identification.<br>
  [ ] The equation computes a Eigenface decomposition for face identification.<br>
  [ ] S is a scatter matrix.<br>
  [ ] W defines a global feature for face recognition.<br>

- Among the following subsets of adversarial factors for face recognition, select the one including only elements that can not be compensated by warping, geometric transformation or standard pixel scalings.<br>
  [ ] Exposure, blurring, pose.<br>
  [X] Compression, age, occlusions.<br>
  [ ] Image resolution, illumination, facial expression.<br>

- In relation to the Kazemi-Sullivan algorithm, select the wrong statement among the following:<br>
  [ ] It is usually based on 68 landmarks.<br>
  [ ] It is based on cascade regressors.<br>
  [X] Split decisions are made on the same pixel set.<br>

- In the definition of fairness, the statement "classification remains the same in a counterfactual world where the individual belonged to a different demographic group" refers to (select the correct assignment):<br>
  [ ] Group fairness.<br>
  [ ] Fairness through awareness.<br>
  [ ] Fairness in relational domains.<br>
  [X] Counterfactual fairness.<br>

- Concerning the use of deep learning solution in face recognition, please select the wrong statement among the following:<br>
  [ ] Training can be time-comnsuming.<br>
  [ ] Training set-ups are usually ideal; real life cases are different.<br>
  [ ] Generalization can be difficult because of bias.<br>
  [X] Large backbone networks for facial features need to be created from large datasets of faces.<br>

- Concerning iris analysis, select the correct statement among the following.<br>
  [X] Iris pattern is determined by a random morphogenetic process.<br>
  [ ] Effectiveness change with age<br>
  [ ] Iris scanners acquire the back of the eye.<br>
  [ ] Eye-dilation drops allow to change the identity.<br>

- In iris recognition, occlusion masks allow to localize ... (select the correct combination of elements)<br>
  [ ] Pupillary boundary, eyelids, eyelashes.<br>
  [ ] Primary specular reflection, eyelids, eyelashes<br>
  [X] Specular reflections, eyelids, strands of hair<br>

- Considering the Mel-frequency Cepstral coefficients, select which among the following statements is wrong.<br>
  [ ] They are the output of a DCT transform.<br>
  [X] They are computed on a uniform frequency grid.<br>
  [ ] They can be computed from the logarithm of absolute FFT coefficients.<br>
  [ ] Spectrum can be computed on partially overlapping segments.<br>

- Considering a generic processing pipeline for a gait identification system, select the correct ordering for the following processing steps:<br>
  [ ] Upsampling and filtering, template matching, template extraction, classification.<br>
  [ ] Upsampling and filtering, template extraction, classification, ample normalization.<br>
  [X] Upsampling and filtering, template extraction, sample normalization, classification.<br>
  [ ] Template extraction, upsampling and filtering, sample normalization, classification.<br>

- Considering a keystroke-based biometric system, select the wrong statement among the following one.<br>
  [ ] The time taken to select, depress and release certain keys is a useful feature.<br>
  [ ] Similar approaches can be adopted for mouse and finger swiping on touch screeens.<br>
  [X] It allow secure and robust identification of the user.<br>
  [ ] It can be used in a multipass authentication.<br>

- Concerning an iris code, select the wrong statement among the following.<br>
  [ ] It is generated from a set of Gabor filters that output complex values.<br>
  [X] Commercial iris codes are made of 2048 sample points.<br>
  [ ] Commercial iris codes are made of 2048 bits + 2048 bit masks.<br>

- Considering the iris code in a biometric authentication system, select the wrong statement among the following ones.<br>
  [ ] Standard iris codes are made of 1024 bits.<br>
  [X] Pixel belonging to eyelids or eyelashes are not skipped thanks to a mask.<br>
  [ ] 128 samples are generated for each sampled radius on the rubber sheet model.<br>
  [ ] Iris code is computed from the phase of Gabor filter response.<br>

- Traditional iris segmentation uses the integro-difference operator maxx0,y0,r∣∣∣Gσ(r)∗∂∂r∮x0,y0,rI(x,y)2πrds∣∣∣.<br>
  [ ] It finds the maximum in the blurred partial derivative with respect to the (x0,y0)coordinates.<br>
  [X] Gσ(r)is a Gaussian filter with radius r and scale σ<br>
  [ ] It can be used to find the parameters of furrows.<br>

