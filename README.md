# PacketSerializer

### Supported Type

```
int
long
short
bool
string
char
double 
list<object>
dictionary<byte, object>
```


### How To Use

#### - Copy & Paste Serializer.cs to your project
#### - Write and use the code below

```
byte[] serializedData = Serializer.Serialize(    " Your Own Data "   );

object deserializedData = Serializer.Deserialize(serializedData);

```

