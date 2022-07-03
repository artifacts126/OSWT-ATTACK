# OSWT-ATTACK

The ordererclient.go, broadcastclient.go, common.go are responsible for submitting transactions on an undercover in the function impactChannel.

Input the number of transactions and the orderer that receives them, and be able to output the average LatencyO of these transactions.

The ordererclient.go should replace the file fabric/internal/peer/common/ordererclient.go. 

The broadcastclient.go should replace the file fabric/internal/peer/common/broadcastclient.go

The common.go should replace the file fabric/internal/peer/chaincode/common.go. 

Re-compile the peer(client, undercover). Then, the undercover invoke a chaincode to submit transactions, and output the average LatencyO.

The undercover inputs:   input_number.txt  input_orderer_endpoints.txt
The undercover output： latency_result.txt