//# patterns
//Making Patterns with Loops 

//For circles

int x = 0; 

int y = 0;

int w = 100;

//for rec

int a = 0;

int b = 0;

int c = 20;

int i = 0;





size(800,800);

while(y <=800){

  w = 100;  //concentric circles pattern 
  
 while(w>0){
 
   fill(random(255),random(255),random(255));
   
   ellipse(x,y,w,w);
   
   w = w - 20;
   
 }
   
   x = x + 100;
   
   if(x > 800) {
   
   if ( x == 850) x = 0;
   
   else x = 50;
   
    x = 0;  
    
    y = y + 100;
    
   }
   
   
 }

   a = 40;
   
b = 40;

//Squares

while (b <= 800){

  fill(random(255),random(255),random(255));
  
rect(a,b,c,c,5);

a = a + 100;

if ( a > 800){

  a = 40;
  
 b = b + 100; 
 
}
 
  

   
 
 
 

 
 

 
 
 
 
 
 
