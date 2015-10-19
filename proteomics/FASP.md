# Filter Aided Sample Prep (FASP)

## Reagents
1. Lysis Buffer (LB)
	* ~~4% SDS~~ 0.5% SDS <- 4% SDS seemed like way too much.
	* 8M Urea
	* 100 mM Tris-HCl pH 7.5
2. Urea Buffer A (UA)
	* 8M Urea
	* 100mM Tris-HCl pH 8.5
	* Recipe:
		* 1 mL - 480 ug Urea, 100 uL 1M Tris, 550 uL H2O
3. Urea Buffer TCEP (UAT)
	* UA + 5mM TCEP
4. Urea Buffer B (UB)
	* 8M Urea
	* 100 mM Tris-HCl pH 8.0
	* Recipe: See UA
5. 0.5 M Iodoacetamide (IAA)
	* 9.25 mg iodoacetamide in 100 uL H2O (keep dark)
6. TEAB
	* 50 mM triethyl ammonium bicarbonate

## Protocol
### Cell Lysis
1. Add LB to cells to lyse, either pellet or dish
	* about 300 uL per 10cm plate
2. Fragment DNA using small gauge needle and syringe
3. Perform BCA or NanoDrop
4. Add DTT and TCEP to 100mM and 10 mM, respectively
5. Boil to finish denaturing

### Digestion
Care - In steps 9-11, about 20 uL should be left after each spin. If more is left, spin longer. We need to have the Urea at low enough concentration for efficient trypsin digestion.

1. Add cell lysate (up to 250 ug) to 10 kDa cutoff NanaSeq spin filters.
  
2. Spin at 14000 g to remove volume
  
3. Add with 200 uL UAT
  
4. Spin at 14000 g for 15 min
  
5. Add with 200 uL UAT
  
6. Spin at 14000 g for 15 min
  
7. Add 100 uL UA with 50 mM IAA and incubate in dark at RT for 30 min
  
8. Spin at 14000 g for 10 min
  
9. Add 100 uL UB and spin at 14000 g for 15 min    
  
10. Add 100 uL UB and spin at 14000 g for 15 min
  
11. Add 100 uL UB and spin at 14000 g for 15 min

12. Add 20 uL H2O, and 12.5 ug Lys-C per uL digest

13. Incubate at 37 C overnight

14. Add 160 uL H2O, and 12.5 ug Trypsin per uL digest

15. Incubate at 37 C for about 8 hrs

16. Spin at 14000 g for 15 min

17. Elute with 50 uL of TEAB, spin at 14000 g for 15 min
