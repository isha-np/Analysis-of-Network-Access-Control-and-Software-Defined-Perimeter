# Analysis-of-Network-Access-Control-and-Software-Defined-Perimeter
This project is part of coursework for the course EEE 598: Introduction to Complex Networks and Machine Learning.

With the rapid growth of mobile devices accessing information networks of various organizations, it is imperative that we build tools that provide the visibility, access control, and compliance capabilities that are necessary to strengthen the security infrastructure of computer networks. Due to the highly interconnected nature of the internet, any breach of security leads to cascading failures which could be detrimental to enterprises and individuals accessing the network. The objectives of the project are as follows:
1) To critically analyze Network Access Control (NAC), with a detailed evaluation of the key features, methodology, impact, advantages, and areas of improvement.
2) To compare computer network security solutions proposed by industry leaders and assess their functionality with respect to the current demands.
3) To compare the conventional NAC approach to a newly defined alternative called Software-Defined Perimeter (SDP).

The internet, or the World Wide Web, is a network in which the vertices are web pages consisting of text, pictures, or other information and the edges are the hyperlinks that allow us to navigate from page to page. This is a directed network since hyperlinks run in only one direction. The resilience of an Internet connection refers to its ability to maintain a compatible level of service under adverse conditions and challenges. These challenges include malicious attacks, software and hardware faults, human mistakes (e.g., software and hardware misconfigurations), and large-scale natural disasters.

Computer network security, also called Cybersecurity, is the process of taking preventative measures to protect the underlying networking infrastructure from unauthorized access, misuse, malfunction, modification, destruction or improper disclosure. The intentions behind most attacks against networks are to gain access to information, damage users’ devices or manipulate systems to gain physical access to facilities. With the aim to enhance cybersecurity of security-constrained networks, two popular protocols are Network Access Control (NAC) and Software Defined Perimeter (SDP).

Four research papers were analyzed for understanding and evaluating NAC and SDP. According to the documentation available, NAC can be defined as a computer networking solution that uses a set of protocols to define and implement a policy. This policy describes how devices can securely access network nodes when they initially attempt to access the network. It restricts the availability of network resources to endpoint devices and users that comply with a defined security policy. NAC can be diagrammatically represented as given below.
![slide5_NACarch](https://user-images.githubusercontent.com/74524978/214175879-ec12de78-102f-4b47-9717-311dfa4318ac.png)

When leaders in technology such as Microsoft, Cisco, VMWare, etc. realized the necessity of protecting data stored in nodes of their information networks, they developed solutions to meet the ever-evolving requirements of network security. Another aim of my project is to critically compare these proposed solutions with respect to the current cybersecurity landscape.

Upon realizing the need to develop solutions better adapted to the cybersecurity requirements of the 2010s, SDP was proposed by the Cloud Security Alliance (CSA) as a security model/framework having a dynamic ability to protect networks. In this framework, every server is hidden behind a remote access server to which a user must authenticate before the services provided by the network are visible and accessible. As a result, the network infrastructure cannot be detected without visible Domain Name System (DNS) information or visible IP addresses. Since it is undetectable by devices/applications that are unauthorized to see it, network-based attacks such as server scanning, denial of service, password cracking, man-in-the middle attacks, etc., can be mitigated.

The architecture of SDP is displayed in the figure below.
![sdp_arch](https://user-images.githubusercontent.com/74524978/214176171-27bd3cd2-ed47-4273-8b69-61c5b9816bf7.jpg)

The third aim of the project was to critically compare NAC and SDP in terms of authentication, encryption, fine-grained access, visibility, and network infrastructure simplicity. Though there is no one single solution which works effectively for all networks and under all circumstances, each solution has its own merits and drawbacks. The choice of approach towards achieving computer network protection should be based on structure of the network and sensitivity of information contained in the network.

The comprehensive results of the analysis have been hidden since this project is part of graded coursework. 
