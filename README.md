# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

![Screenshot (26)](https://github.com/user-attachments/assets/b85951fc-457d-43d7-a406-a19ddff6b4c3)
![Screenshot (34)](https://github.com/user-attachments/assets/b8fe0e4f-e8f5-48de-aa82-0d342fcc9c65)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module func1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

```
```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

```


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Sameer shariff M RegisterNumber: 24900559/


**RTL realization**

**Output:**

**RTL**

 ![Screenshot (27)](https://github.com/user-attachments/assets/ea0222f7-2e75-4459-8b6b-44a0925b507a)
 ![Screenshot 2024-12-01 191304](https://github.com/user-attachments/assets/8dea6029-95bf-433d-911f-0839715b4583)




**Timing Diagram**

**Result:**
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Bootstrap Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MySite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="bg-primary text-white text-center py-5">
    <div class="container">
      <h1 class="display-4">Welcome to dyslexify</h1>
      <p class="lead">Empowering Minds with Smart Assistive Technology</p>
      <a href="get-started.html" class="btn btn-light btn-lg mt-3">Get Started</a>
    </div>
  </header>

  <!-- Main Content -->
  <section class="container my-5">
    <div class="row">
      <div class="col-md-6">
        <h2>About This Page</h2>
        <p>Welcome to dyslexify, your personalized companion designed to support individuals with dyslexia in reading, writing, and learning with confidence. Our mission is to make literacy accessible and enjoyable for everyone. Whether you're a student, professional, or parent, our tools are crafted to provide a smoother reading and learning experience.</p>
      </div>
      <div class="col-md-6">
        <h2>Feautres include</h2>
        <p>Text-to-Speech: Listen to written content in a natural voice.</p>
        <p>Speech-to-Text: Convert spoken words into written text with ease.</p>
        <p>Font Customization: Choose dyslexia-friendly fonts and adjust spacing for better readability.</p>
        <p>Reading Guide & Highlighting: Stay focused with real-time text highlighting and reading overlays.</p>
        <p>Note-Taking & Organizing Tools: Simplify writing and manage your thoughts clearly.</p>
      </div>
    </div>
  </section>

  

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Get Started - Dyslexify</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" />
</head>
<body>

  <header class="bg-dark text-danger text-center py-5">
    <div class="container">
      <h1 class="display-4">Team Ironfist</h1>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100 text-center">
            <div class="card-body">
              <h5 class="card-title">Oviya B</h5>
              
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 text-center">
            <div class="card-body">
              <h5 class="card-title">Nusrath Fathima S</h5>
              <p class="card-text">Team Leader</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 text-center">
            <div class="card-body">
              <h5 class="card-title">Pramila T</h5>
              
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    </body>
    </html>



Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

