Word lists from my readings
 
```ruby
a = %w[ Alice Android APUE 
        Dinosaur 
        English 
        Happier 
        IETLS
        Japanese 
        Leetcode 
        Networking 
        OSTEP 
        Recipe 
        Solitude stdlib 
        TCP/IP 
        Wikipedia ]
a.shuffle.first(5).each(&method(:p))
```
