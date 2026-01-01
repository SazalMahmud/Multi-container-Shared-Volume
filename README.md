 # Create the pod using the following command:
    
    Verification
-Check Pod Status
# Ensure the pod is running without errors using the following command:

    kubectl get pods my-pod

 --View Logs from Each Container
# Check the logs of container c1:
    kubectl logs my-pod -c c1
# Check the logs of container c2:
    kubectl logs my-pod -c c2
# Check the logs of container c3:
    kubectl logs my-pod -c c3



