# Thesis dataset

This is the Hub-like dataset used for my bachelor thesis. Each Hub-like was given to Gemini Advanced in a separate and new chat and with these different prompts:

### Prompt 1

```
I have the following Java classes. Do you see any architectural smell? These are the only classes in my project.

Do not explain what an architectural smell is or how to remove it, just say if you see some or not. You don't need to specify which classes are involved in the smell.

<Java code>
```


### Prompt 2

```
I have the following Java classes. Do you see any architectural smell? These are the only classes in my project. I am looking for these architectural smells: Hub-like dependency, Cyclic dependency, God component, Unstable dependency, Cyclic hierarchy, Deep hierarchy, Wide hierarchy.

Do not explain what an architectural smell is or how to remove it, just say if you see some or not. You don't need to specify which classes are involved in the architectural smell.

<Java code>
```


### Prompt 3

```
I have the following Java classes. Do you see any hub-like architectural smell? These are the only classes in my project.

Do not explain what an architectural smell is or how to remove it, just say if you see some or not. You don't need to specify which class is the hub-like class.

<Java code>
```
### Prompt 4

```
I have the following Java classes. Do you see any hub-like architectural smell? These are the only classes in my project. In particular, an hub-like architectural smell arises when an abstraction has a large number of incoming and outgoing dependencies, making the dependency structure look like a hub.

Do not explain what an architectural smell is or how to remove it, just say if you see some or not. You don't need to specify which class is the hub-like class.

<Java code>
```

## Projects

To obtain the code involved in the smells, the following projects were analyzed with Arcan:

- **Insert the final list of analyzed projects** 


