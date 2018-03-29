# Angular @input

Angular one component value print or recieve the another component,
 @Input is a decorator to mark an input property,

Parent component or another child component

  variable value set example(count:number=10)
  inside parent html file added <app-child [percount]= 'count' ></app-child>
  
 child component
 
     count value pass to child component  
{{percount}} print in child 
       
