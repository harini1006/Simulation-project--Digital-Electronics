

## PROGRAM:
```python
module skillassessment(x,y,z,f);
input x,y,z;
output f;
wire a,b,c,d,e;
not (a,x);
not (b,y);
not (c,z);
and (d,a,b,c);
and (e,x,y,c);
or (f,d,e);
endmodule
```
## RTL Schematic:
![image](https://github.com/harini1006/Simulation-project--Digital-Electronics/assets/113497405/c8176226-7c04-4d01-9a2d-71fd2b85beea)
## TIMING DIAGRAM:
![image](https://github.com/harini1006/Simulation-project--Digital-Electronics/assets/113497405/b09bad41-24a9-40f7-981e-57389c1726c4)

