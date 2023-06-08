# Master Thesis - TPK4960
This project is inline with the course TPK4960 Robotics and automation, master thesis Spring 2023.
The objective of the project is to examine the effectiveness of RFF using to approximate kernels in various regression problems.

Key-words: Learning, nonlinear dynamics, regularization, LASA, RKHS, RFF, curl-free kernel, Gaussian separable kernel, Hamiltonian dynamics, symplectic kernel

## Main file and notebook structure
    . 
    ├── TPK4960                      # 
        ├── src                      # Source files for the project                              
            ├── hamilton             # Parent directory for all files related to Hamiltonian systems
                ├── hamilton_figures # Parent directory for storing saved plots to Hamiltonian models
                ├── RFF_parameters   # Parent directory for storing parameters used in regression problems
            ├── lasa                 # Parent directory for all files related to the Lasa problem
                ├── Dataset          # Dataset directory for Angle-shape and S-shape used in regression problems
                ├── lasa_figures     # Parent directory for storing saved plots to LASA models
                ├── RFF_parameters   # Parent directory for storing parameters used in regression problems


### Libraries
Other than well-known NumPy and SciPy libraries used in the code, we have also used some other Python tools for optimization and numerical
solution solving:
- [PICOS](https://pypi.org/project/PICOS/)
- [MOSEK](https://www.mosek.com/)


### Installation
Note that if you want to run the simulations where the regression problem is solved using MOSEK and PICOS, you need to run the following command
#### PICOS
```sh
pip install PICOS
```
#### MOSEK
```sh	
pip install MOSEK
```
For MOSEK, you need to ask for a licence, and then add it to the folder where Mosek is installed. See: https://www.mosek.com/products/license-agreement/

### Thesis partners
<table style="color:blue;">
  <tr>
  <td align="center"><a href="https://github.com/helenatp"><img src="https://avatars.githubusercontent.com/u/73463951?v=4" width="100px;" alt=""/><br /><sub><b>Helena Phan</b></sub></td>
  <td align="center"><a href="https://github.com/vildetk"><img src="https://avatars.githubusercontent.com/u/78173372?v=4" width="100px;" alt=""/><br /><sub><b>Vilde Taklo Kenworthy</b></sub></td>
  </tr>
</table>
