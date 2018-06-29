# subl3

My additional code snippets for Sublime-Text-3-C++. Run - 

```
cd ~/.config/sublime-text-3/Packages/  
git clone https://github.com/RezwanArefin01/subl3.git 
mv subl3/ C++/
cd C++/
sudo cp timeout /bin
```

Precompile `bits/stdc++.h` located in `/usr/include/c++/<g++ version>/x86_64-pc-linux-gnu/` using this - 

```
g++ -DLOCAL -O2 stdc++.h
```
