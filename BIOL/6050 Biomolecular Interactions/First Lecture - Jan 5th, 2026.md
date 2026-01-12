**Measurement VS Determination  
  
Measurement requires a reference standard (Unit).  
Determination comes from Measurement.  
Compound Measurement might happen.  
  
Screening is used for drug development, and it’s expensive.  
  
  
What are the Biomolecular Interactions?  
- Recognition of affinity  
- Regulation in Cell.  
  
Human optimal body temperature, at which the majority of reactions can be catalyzed.  
  
Signal: ligand binds receptors on the cell membrane and changes the inner environment.  
  
  
Two forces, attraction and repulsion, are involved in Interactions.  
  
  
Quantum mechanics is getting inapplicable as the molecules become more complex; however, at a certain point, it can be applicable again as the scale increases.  
  
  
Noncovalent Bonding  
  
Three main types of non-covalent bonds: hydrogen bonding, ionic bonding, and van der Waals interactions.  
Hydrophobic interactions cannot be called hydrophobic bonds.  
  
Types of intermolecular interactions  
  
A. Charge-Charge | 100-300 KJ/mol  
B. Charge-Dipole | 50-200 KJ/mol  
C. Dipole-Dipole | 5-50 KJ/mol  
D. Charge-Induced Dipole  
E. Dipole-Induced Dipole  
F. Dispersion | <5 KJ/mol  
G. van deer Waals repulsion  
H. Hydrogen Bond | 5-160 KJ/mol (5 is for H2O 160 for F-H)  
  
Hydrophobic effect is not force, but exclusion from  
  
  
****Affinity (multi-valent) Interactions****  
  
Affinity interactions are strong, highly-specific binding of macromolecules through establishing multiple weak non-covalent bonds between different moieties of the molecules.  
Affinity interactions are typically entropy-unfavourable  
Moleculear shapes are important for affinity interactions as they allow molecules to establish many non-covalent bonds (if groups required for such bonds are in right locations)  
- The Key and Lock concept (Emil Fisher, 1894) does not consider the change of conformations upon establising the bonds  
- The Hand and Glove (Induced Fit) concept (Daniel Koshland, 1958) suggests that the coomplete fit (with regards to conformations) is only established when all multiple non-covalent bonds are established.  
  
Ex: Enzyme-substrate, Antibody-Antigen, Ligand-Receptor, Transcriptioin factor-DNA, Macromolecular machinery (e.g. ribosomes, actin filaments, microtubules), DNA-DNA  
  
Role of Affinity Interactions in Biology  
- Catalytic activity  
- Immune response  
- Signal transductions  
- Cell-cell recognition  
- Viral and bacterial infections  
  
- Role of Affinity Interactions in Technology  
- Affinity purification**

**- Immunoassays  
- Hybridization assays  
- Affinity methods for studying affinity interactions  
- Screening of libraries for drug candidates and diagnostic probes  
  
∆G = -T∆Suniv = ∆H - T∆Ssys  
  
The reaction proceeds spontaneously if ∆G < 0  
Statistical definition of entropy: S = k in w, where k = R/Na is the Boltzman’s constant and w is the number of accessible microstates in the system, that result in the same energy.  
  
Keq = e^(∆G˚/RT) -> ∆G˚ = -RT ln Keq  
  
  
∆G˚ is the Gibbs energy change under standard conditioins for all concentrations equal to 1M (activities equal to 1)  
For non-standard conditions (different from 1M concentrations or activities of 1):  
∆G = ∆G˚ + RT lnQ  
Where Q is the reaction quotient  
  
Illustration of practical use of thermodynamics:  
1. Keq is determined experimentally from measuring concentrations at equilibrium**

**2. ∆G˚ is determined from: ∆G˚ = -RT ln Keq  
3. ∆G for non-standard conditions is found ∆G = ∆G˚ + RT ln Q  
  
A + B <-> C  
T + L <-> C (Target + Ligand <-> Complex)  
  
****Molecular Docking (ligand into a protein)****  
Molecular docking is a method which predicts the preferred mutual orientation of two molecules to form a stable complex  
Binding energy of the complex in the preferred orientation can be estimated  
  
Concept: One molecule is rotated around the other one and different orientation are brobed for “binding”  
  
Binding is understood either as 1) shape complementarity or as 2) loest energy in the “energy profile”  
  
Shape complementarity method  
4. Shapes of both protein and ligand are considered rigid and depicted in a 3-D grid system with each point being either:  
- Inside the molecule, or  
- on the surface of the molecule, or  
- outside the molecule  
2. The orientation with the largest surface contact is searched  
3. Method is fast when combined with Fast Fourier Transform -> can screen a large number of ligands  
4. It can give many false positives as binding strength depends not only on shapes but also on the availability of bonds. Ideally, the method must be followed by a docking simulation to exclude false positives or by experiment  
5. Used for protein-protein interactions  
  
∆H < 0 ∆S > 0: Spontaneous at all temperatures  
∆H > 0 ∆S > 0: Spontaneous at high temperatures  
∆H < 0 ∆S < 0: Spontaneous at low temperatures  
  
——**

  

**Kenetics  
  
Relation between rate constants and equilibrium constants  
All complexes C, no matter how many bonds are between T and L, are treated as identical in kinetics  
  
T + L <-> C  
Units for the rate constants kon = (M^-1s^-1) koff (s^-1)  
Rate of reaction = dC / dt = - dT / dt = - dL / dt = kon TL - koff C  
At equalibrium: T, L, C = const, and dC / dT = - dt / dt = dL / dt = 0 ->  
kon TL - koff C = 0 -> koff / kon = TL / C = Kd = Kb^-1 -> Kd = koff / kon (M)  
(Ka = Equailibrium Constant, koff/kon: Reaction Constant)  
  
If T and L of arbitrary concentrations are mixed, the kinetics is, in geneal, not exponential. However, the kinetics can be made exponential if the reaction is made “pseudo-first order”  
- Let’s define T0 and L0 as total concentrations of T and L; they can be understood as concentrations Tt=0 and Lt=0 immediately after mixing T and L but before the reaction proceeds to any significant extend towards the formation of C T0 and L0 can also be defined from mass balance that is satisfied at any time:  
  
T0 = T + C, L0 = L + C  
  
Pseudo-first order reaction  
Let’s assume that T0 >> L0 then T = (almost) constant = T0  
Pseudo-first order rate constant Kon T0 = Kon’  
Rate of reaction : dC / dT = - dt / dt = dL / dt = konT0L - koff C = kon’ L - koff C -> dC / dt = kon; L - koff C  
  
We will solve the above equation for C(t) with initial concentrations: Ct=0 = 0, Tt=0 = T0, Lt=0 = L0  
From massbalance L = L0-C  
dC/dt = kon’L - koffC = kon’ (L0-C) - koff C = kon’ L0 - kon’C - Koff C = kon’L0 - (kon’ + koff) C, lets separate the two variables: C and t  
  
dC / kon’L0 - (kon’ + koff) C = dt, this is an ordinary differential equation with separated variables C and t  
If a = -(kon’ + koff), b = kon’L0, and x=C then the differential equatioin can be rewritten:  
dx / ax+b = dt, and the goal is to solve this equation and fine fucntion x(t)  
This equation can be directly integrated:  
integral(dx / ax + b) = integral(dt) = t + C**