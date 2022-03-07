Experiment_8

Infix to Postfix Conversion Using Stack

Enter the Expression : A*B+C/D^2

 Token: A        stack :         postfix : A
 Token: *        stack : *       postfix : A
 Token: B        stack : *       postfix : A B
 Token: +        stack : +       postfix : A B *
 Token: C        stack : +       postfix : A B * C
 Token: /        stack : + /     postfix : A B * C
 Token: D        stack : + /     postfix : A B * C D
 Token: ^        stack : + / ^   postfix : A B * C D
 Token: 2        stack : + / ^   postfix : A B * C D 2 
 Postfix: AB*CD2^/+
