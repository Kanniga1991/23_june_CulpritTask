# 23_june_CulpritTask(PART-1)
find the error task 

        1)
        <!DOCTYPE html>
        <html>
        <body>
         <script>
         alert( “I’m JavaScript!’);
         </script>
         Whats the error in this ?
        </body>
        </html>
        ANS- DOUBLE QUOTATION OPENING AND SINGLE QUOTATION CLOSING
                      2)
                      <!DOCTYPE html>
                      <html>
                      <body>
                       <script src=”script.js”></script>
                      </body>
                      </html>
                      alert(“I’m invoked!”);
                      ANS -SOME QUOTATION PROBLEM IN ALERT TAG
      3)
    <!DOCTYPE html>
    <html>
    <body>
    <script src=”script.js”></script>
    </body>
    </html>
      alert("I'm JavaScript!");
      alert('Hello') // this line is not having semicolon
      alert(`Wor
      ld`)
      alert(3 +
      1
      + 2); // this is multiple line code and its working
      ANS - "I'm JavaScript!"
             Hello
             Wor
             ld
             6
                        4)
                      <!DOCTYPE html>
                      <html>
                      <body>
                       <script src=”script.js”></script>
                      </body>
                      </html>
                      let admin=9, fname=10.5; 
                      fname = "Guvi";
                      lname = "geek"
                      admin = fname+lname;
                      alert( admin ); // "Guvi geek"
                      ANS - admin = fname+" "+lname;
          5)
        <!DOCTYPE html>
        <html>
        <body>
         <script src=”script.js”></script>
        </body>
        </html>
        let fname=10.5; 
        fname = "Guvi";
        lname = "geek"
        let name = fname+lname;
        alert( 'hello ${name}' );
        ANS - alert( "hello"+" "+ fname + " "+lname  );

                               6)
                               Fix the below to alert sum of two numbers
                               let a = prompt("First number?");
                               let b = prompt("Second number?");
                                alert(a + b);
                                  ANS - //do parseint
                                      let a =+ prompt("First number?");
                                      let b = + prompt("Second number?");
                                      alert(a + b);
                                      
                                    7)
                                Explain Why the Code is blasted and how to diffuse it and get “Diffused”.
                                
                                var a = "2" > "12";
                                //Don't touch below this
                                if (a) {
                                  console.log("Code is Blasted")
                                }
                                else
                                {
                                  console.log("Diffused") 
                                }  
                                ANS -// if not equal to a;
                                var a = "2" > "12";
                                //Don't touch below this
                                if (!a) {
                                console.log("Code is Blasted")
                                        }
                                 else
                                        {
                                console.log("Diffused") 
                                        }
                      8)
                      How to get the success in console
                      
                      let a = prompt("Enter a number?");
                      //Don't modify any code below this
                      if (a) {
                       console.log( 'OMG it works for any number inc 0' );
                      }
                      else
                      {
                       console.log( "Success" );
                      }
                      ANS - use parseint for getting variable so that else part execute.
                      let a = +prompt("Enter a number?");
                      //Don't modify any code below this
                      if (a) {
                       console.log( 'OMG it works for any number inc 0' );
                      }
                      else
                      {
                       console.log( "Success" );
                      }

                            9)
                            How to get the correct score in console.

                            let value = prompt('How many runs you scored in this ball');
                            if (value === 4) {
                                  console.log("You hit a Four");
                            } else if (value === 6) {
                                  console.log("You hit a Six");
                            } else {
                                  console.log("I couldn't figure out");
                            }
                            ANS - use parseint to get the runs scored.
                            let value = +prompt('How many runs you scored in this ball');
                            if (value === 4) {
                                  console.log("You hit a Four");
                            } else if (value === 6) {
                                  console.log("You hit a Six");
                            } else {
                                  console.log("I couldn't figure out");
                            }

                          10)
                          Fix the code to welcome the boss
                             // You cant change the value of the msg
                                let message;
                                if (null || 2 || undefined )
                                {
                                 let message = "welcome boss";
                                }
                                else
                                {
                                 let message = "Go away";
                                }
                                  console.log(message);
                                ANS - remove that "let" datatype inside the blocks.
                                let message;
                                if (null || 2 || undefined )
                                {
                                 message = "welcome boss";
                                }
                                else
                                {
                                  message = "Go away";
                                }
                                  console.log(message);

      11)
      Fix the code to welcome the boss
      let message;
      let lock = 2;
      //Dont change any code below this
      if (lock && " " || undefined )
      {
        message = "Go away";
      }
      else
      {
       message = "welcome";
      }
      console.log(message);
      ANS - removing the declared/assigned value for lock.
      let message;
      let lock ;
      //Dont change any code below this
      if (lock && " " || undefined )
      {
        message = "Go away";
      }
      else
      {
       message = "welcome";
      }
      console.log(message);

                               13)Change the code to print even numbers
                               //You are allowed to modify only one character 
                                  for (let num = 2; num <= 20; num += 1) {
                                    console.log(num)
                                  }
                                  
                                ANS - change the increment to num=num+2.
                                for (let num = 2; num <= 20; num += 2)
   
    14)Change the code to print all the gifts
    let gifts = ["teddy bear", "drone", "doll"];
      for (let i = 0; i < 3; i++) {
        console.log('Wrapped ${'gifts[i]'} and added a bow!');
      }
    ANS - 
    let gifts = ["teddy bear", "drone", "doll"];
      for (let i = 0; i < 3; i++) {
        console.log(gifts[i] +" "  +"added a bow!")
      }
      
                14) what is the message printed and why?
                var lemein = “0”;
                  var lemeout = 0;
                  var msg = “”;
                  if (lemein) {
                   msg += “hi”;
                   }
                  if (lemeout) {
                   msg += ‘Hello’;
                  }
                  console.log(msg);
                               
                  ANS - "hi" is the message printed because if(), is followed by else if() or else () and "0" is the string                  
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
                   
   
                   
