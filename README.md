# **[16,21,11,8,12,22]** -> Merge Sort
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

## **CEVAP 1:**

                            [16,21,11,8,12,22]                                
            [16,21,11]                              [8,12,22]
        [16]          [21,11]                    [8]         [12,22]
        [16]       [21]     [11]                 [8]      [12]     [22]
        [16]          [11,21]                    [8]         [12,22]
            [11,16,21]                              [8,12,22]
                            [8,11,12,16,21,22]

## **CEVAP 2:**
```

2x=n            x= logn          O(nlogn)

```

[patika.dev](www.patika.dev)