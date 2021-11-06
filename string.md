# Rabin-Karp Algorithm
```sh
function RabinKarp(string s[1..n], string pattern[1..m])
    hpattern := hash(pattern[1..m]);
    for i from 1 to n-m+1
        hs := hash(s[i..i+m-1])
        if hs = hpattern
            if s[i..i+m-1] = pattern[1..m]
                return i
    return not found
```

一个基础实现，不一定好
```java
int rabinKarp(String s, String p) {
    int hashpattern = p.hashCode();
    for (int i = 0; i < s.length() - p.length() + 1; i++) {
        String cur = s.substring(i, i + p.length());
        int curhash = cur.hashCode();
        if (hashpattern == curhash && cur.equals(p)) {
            return i;
        }
    }
    return -1;
}

```
可以参考下普林斯顿的版本：

https://algs4.cs.princeton.edu/53substring/RabinKarp.java.html