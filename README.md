python math expression parser is a python project where you can parse or evaluate math expressions.

This algorithm does not use a decision tree. It is a recursive algorithm.

Installation

pip install pymep

Here you can see some examples:

  Real Numbers:    
	
	from pymep.realParser import parse
	from pymep.realParser import eval


	#Real Expresion parser
	fx="cos(10)"
	print(parse(fx))
	xi=5
	fx = "1 + x"
	print(eval(fx, xi))
	

  For complex Numbers:
  
    from pymep.complexParser import parse
	from pymep.complexParser import eval
	from pymep.complex import Complex

	#Operation with complex numbers
	a = Complex(1,2)
	print(a.__radd__(10).__complex__())
	print(Complex.radd(10, a).__complex__())


	#Complex Expresion parser
	fx="cos(10+2j)"
	print(parse(fx).__complex__())
	xi=5
	fx = "1 +j+x"
	print(eval(fx, xi).__complex__())
      
 There is a full list of examples inside!!

Enjoy it!!
