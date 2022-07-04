# OSWT-ATTACK

You need to download the two projects fabric (https://github.com/hyperledger/fabric/) and golang (https://github.com/golang/go) beforehand, and then compile them after replacing the specified files.

impactChannel contains specific files. Replace the corresponding files in the original project with these files and compile them to obtain the undercover responsible for submitting the transaction in the function impactChannel in Algorithm 1.
(Another way of generating transactions is shown in https://github.com/hyperledger/caliper)

dos attack contains specific files. Replace the corresponding files in the original project with these files and compile them to obtain the DoS node responsible for launching DoS attack.

countermesure contains specific files. Replace the corresponding files in the original project with these files and compile them to obtain the orderer with the countermesure.