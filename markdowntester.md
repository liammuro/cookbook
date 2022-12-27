# markdowntester

## ingredients




<details>
    <summary>Toggle Switch</summary>
    Test
</details>



```mermaid
	graph TD;
		node0((0))-->node1((1)) & node2((2));
		node1-->node3((3)) & node4((4));
		node2-->node5((5)) & node6((6));
```

Problem 3: Huffman encoding
8 points total; individual-only

Consider the following table of character frequencies:

| Character | Frequency | 
| - | - | 
| o | 6 |
| f | 9 |
| l | 13 |
| c | 22 |
| a | 30 |

1. (6 points) Show the Huffman tree that would be constructed from these character frequencies by editing the diagram that we have provided in section 3-1 of ps9_partI. It includes the some of the necessary nodes and edges, but you should create more of them as needed, move them into the appropriate positions, and connect them.

2. (2 points) Using the Huffman tree from part 1, what will be the encoding of the string focal?


```mermaid
    graph TD;
        charo("o | 6")
        charf("f | 9")
        charl("l | 13")
        charc("c | 22")
        chara("a | 39")

        node0("- | 15") --- charo & charf
        node1("- | 28") --- charl & node0
        node2("- | 43") --- charc & node1
        node3("- | 82") --- chara & node2

```