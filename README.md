<h1 align="center">Deploy scalable NoSQL database cluster</h1>


Using noSQl Database for creating cluster of mongoDB and python Flask(backend services) for managing the website.
>  ### Access Services Running on Clusters:

You can connect to nodes, pods, and services from outside the cluster using one of several methods:
 - I used bash to run the pods and services.Access is provided by a cluster node or pod.
  - Run a pod and then use kubectl exec to connect to a shell within it.
   - From that shell, you can connect to other nodes, pods, and services.

![newservices](https://user-images.githubusercontent.com/75021117/144194460-9013dfbc-ce87-482d-8ca8-eade3ef2ec14.JPG)

>  ### Check Status of pods
The pod status command is used to check the status of Kubernetes pods.
If the status.phase of a pod is Succeeded or Running, it returns OK.

![pods](https://user-images.githubusercontent.com/75021117/144194358-e0b4be06-d680-484a-9255-eac361a7ec66.JPG)


>  ### Deployment Status
To see if the Deployment was created, used kubectl get deployments.

![get deploy](https://user-images.githubusercontent.com/75021117/144194810-829562da-6839-491a-b5fa-8bb7deb43b75.JPG)
>  ### Website Demo
<h3 align=center>Created a website that printing a</h2>
<h2 align=center>&nbsp;Welcome :wave:to Tasks app! I am running inside app.....</h2>



![11](https://user-images.githubusercontent.com/75021117/144219587-e5b386a6-3899-453d-894a-b2f0b1bdfc4c.JPG)

- All activities on  website are done by sending requests On Flask api and getting the output, which are then executed on the MongoDB database.

- Included Database Is running on kubernetes.




