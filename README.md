# ethereum-android-sample
Sample project of android go-ethereum client 

## Dependency

~~~
dependencies {
    ... 
    
    compile 'org.ethereum:geth:1.6.6'
}
~~~

## Usage Sample

~~~
  Node node = null;
        Enode enode;
        try {
             node = Geth.newNode("",new NodeConfig());
        } catch (Exception e) {
            e.printStackTrace();
        }

        NodeInfo nodeInfo = node.getNodeInfo();
~~~
