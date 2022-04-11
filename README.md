# turutururum
moon
import sympy as sym
x = sym.Symbol('x')
y = sym.Symbol('y')
sym.expand ((x + y) ** 6)
import sympy as sym
sinx = sym.Symbol('sinx')
cosx = sym.Symbol('cosx')
sym.trigsimp(sinx/cosx)
sym.series(sym.cos(x), x)
import sympy as sym
sym.limit(sym.sin(x) / x, x,0)
import sympy as sym
sym.diff(sym.log(x), x)
