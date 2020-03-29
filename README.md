# Network Research - Topic 1


## What is an IP network?

- An IP network is a communication network that uses Internet Protocol (IP)
to send and receive messages between one or more computers.

## What is an IP?

- Internet Protocol (IP) a digital media transport system that runs
over standard IP networks.

- There are two different types of IP's:

  - IP Version 4 also written as IPv4
  - IP Version 6 also written as IPv6

## IPv4

- The IPv4 address is a 32-bit number that uniquely identifies a network interface
on a machine. An IPv4 address is typically written in decimal digits, formatted
as four 8-bit fields that are separated by periods.

## With IPv4 (NO SUBMASK) How many IP can we have in the world? (SOLUTIONS)

-

## IP and Binary

The IP Address: 154 . 31 . 16 . 13

- Separated into 4 bytes.
- The next sections will demonstrate how we can simply the IP into a binary.

## Calculating the IP into Binary

### STEP 1

The IP Address: 154 . 31 . 16 . 13

STEP 1: 154 - 128 = 26 (TRUE = 1)
```
128	64	32	16	8	4	2	1
1	 	 	 	 	 	 	 
```

STEP 1.2: 26 - 64 = -38 (FALSE = 0)
```
128	64	32	16	8	4	2	1
1	0
```

STEP 1.3: 26 - 32 = -6 (FALSE = 0)	 	 	 	 	 	 
```
128	64	32	16	8	4	2	1
1	0	0
```

STEP 1.4: 26 - 16 = 10 (TRUE = 1)
```  
128	64	32	16	8	4	2	1
1	0	0	1
```

STEP 1.5: 10 - 8 = 2 (TRUE = 1)
```
128	64	32	16	8	4	2	1
1	0	0	1	1	 	 	 
```

STEP 1.6: 2 - 4 = -2 (FALSE = 0)
```
128	64	32	16	8	4	2	1
1	0	0	1	1	0	 	
```

STEP 1.7: 2 - 2 = 0 (TRUE = 1)
```
128	64	32	16	8	4	2	1
1	0	0	1	1	0	1	 
```

STEP 1.8: 0 - 0 = 0 (FALSE = 0)
```
128	64	32	16	8	4	2	1
1	0	0	1	1	0	1	0
```
- 154 Decimal Number is  1 0 0 1 1 0 1 0 in Binary.  
- 128 + 16 + 8 + 2 = 154  

### STEP 2

STEP 2.1: 31 - 128 = FALSE (0)
```
128	64	32	16	8	4	2	1
0
```

STEP 2.2: 31 - 64 = FALSE (0)
```
128	64	32	16	8	4	2	1
0	0	 	 	 	 	 	 
```

STEP 2.3: 32 - 32 = FALSE (0)
```
128	64	32	16	8	4	2	1
0	0	0
```

STEP 2.3: 31 - 16 =  TRUE (1)
```
128	64	32	16	8	4	2	1
0	0	0	1
```

STEP 2.4: 15 - 8 = TRUE (1)
```
128	64	32	16	8	4	2	1
0	0	0	1	1	 	 	 
```

STEP 2.5: 7 - 4 = TRUE (1)
```
128	64	32	16	8	4	2	1
0	0	0	1	1	1	 	 
```

STEP 2.6: 3 - 2 = TRUE (1)
```
128	64	32	16	8	4	2	1
0	0	0	1	1	1	1	 
```

STEP 2.7: 1 - 1 = TRUE (1)
```
128	64	32	16	8	4	2	1
0	0	0	1	1	1	1	1
```
- 31 Decimal Number is 0 0 0 1 1 1 1 1 in Binary.  
- 16 + 8 + 4 + 2 + 1 = 31

### STEP 3

```
128	64	32	16	8	4	2	1
0	0	0	1	0	0	0	0
```
- Decimal Number 16 is 0 0 0 1 0 0 0 0 in Binary.  

### STEP 4

```
128	64	32	16	8	4	2	1
0	0	0	0	1	1	0	1
```
- Decimal Number 13 is 0 0 0 0 1 1 0 1 in Binary.
- 8 + 4 + 1 = 13
