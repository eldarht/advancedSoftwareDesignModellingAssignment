# advancedSoftwareDesignModellingAssignment

The ecore model that contains the model relevant for assignment 1 can be found in:

```
no.tdt4250.assignment1.model/model/courceList.ecore
```

Features that the model should be able to cover:

- [ ] Courses mandatory/elective
	- [x] Status can be O(obligatory), VA(elective), M2A(At least two in group) or other
	- [x] Status can differ between studyprogrammes.
	- [ ] Status defines a constraint/validation that proibits certain combinations automatically
	- [x] Course can be mandaroty for one specialization and elective for an other.
- [ ] Master must contain a minimum of Higher level courses.
- [x] Containment relation.
- [x] Container relation.
- [x] Standard relation.
- [x] Recurcive relation.
- [x] Class attribute.
- [x] Enum.
- [ ] Abstract class
- [ ] Super class
- [x] Class derived attribute. __Example: CourceSpecification name attribute__
- [x] OCL defined getter/setter __Example: CourceSpecification name attribute__
- [x] OCL defined validation __Example: EvaluationForm: weightMustBeComplete __
- [ ] Java defined validation.
- [x] 1 to 1 and 0 to many multiplicity.
- [x] .xmi file with test data.
- [ ] Faculty owns courses.
- [x] Study programmes can change from year to year.
- [x] Courses can change from year to year.
- [x] Courses can be taught either at spring, autumn or both.
- [x] Programmes can be of bachlor, master, phd, etc..

Note: The department.xmi file contains invalid information as the test data is not complete. It is still usefull for testing the system.