After a few rounds of closed discussions and preparations within the steering team of JuliaQuantum, we have formed a rough roadmap for the test-run phase of our projects. I briefly collect some important information and assignments below for followups and feedback. Besides, I would like to sincerely thank Jarrett (jrevels), Alex (acroy), Jutho and Jiahao for their outstanding contributions and dedications to the initiative of JuliaQuantum, for their profound works on building fundamental blocks for our present and future projects, and for their key roles played on turning our needs to the maturity of JuliaLang. For these reasons above but not limited, I have promoted them on the owners’ board of this organization, AKA, the steering team of JuliaQuantum. I believe, through the unremitting efforts of our community, JuliaQuantum will play a significant role on promoting quantum science and technology in the near future.    

1. Establish one or more fundamental and organizational projects for quantum representation basis and dynamics solvers.
    - [ ] QuantumBase project for basic quantum representations. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/6).
    - [ ]  Interface to other relevant packages.  [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/7).
    - [ ] Call for Quantum dynamics solvers. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/8).
    
    

2. Encourage to share and collaborate on open-source Julia projects based on the existing JuliaQuantum projects through the organization and improve the libraries as a return. 
    - [ ] Update JuliaQuantum website with enriched information. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/9).
    - [ ] Rebuild or interface with quantum projects written in other programming languages through collaborations. Also see [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/7)
    - [ ] Unify documentation interface and the workflow of organizational projects. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/10)
    - [ ] Organization-wide agreements to be improved and examined in practice. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/3)

3. Form an academic consultant committee and a Julia organizational supporting team. 
    - [ ] Academic consulting committee program. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/11).      
    - [ ] Form a functional technical supporting and steering team through working together in practice. (General questions regarding Julia should go to [Julia-user Google discussion group](https://groups.google.com/d/topic/julia-users/).) 
    - [ ] Encourage people to join the professional academic/technical teams through our website and our network. See what you can do... [Ref](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/9).

4. The second wave of broadcasting our project to a broader public domain -- once we are ready. 
    - [ ] JuliaQuantum will be presented in SQuInT workshop in Berkeley in the coming Febrary. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/12).
    - [ ] JuliaQuantum in the social network. [Details](https://github.com/JuliaQuantum/JuliaQuantum.github.io/issues/13).

5. Future work for the next organizational milestone. Note: it is good to leave this session open and plan ahead. Here, I collect some preliminary ideas from the discussions with various people. Brainstorms and proposals may be posted under this thread, especially for those with a responsible leader. 

    1. Various Quantum dynamic solvers under JuliaQuantum. Once some building blocks like the [QuBase.jl](https://github.com/JuliaQuantum/QuBase.jl) project are done, and once our members gain broad enough experiences through the interfacing project, we should be able to target at this one. Leaders and candidate projects are still open to propose. 

    2.  Quantum control in real time.—We need feedbacks from people who have been committing on similar tasks, and leave this possibility open for future works. In fact, I proposed that we can use Julia for quantum control beyond the technical computing task that Julia was initially aiming at. Collaborating with developer teams of Parallela and other ARM-based open hardware projects might be helpful for this purpose. It seems we are not at that stage yet. Here are two valuable points from Jiahao:

      * <cite> ARM support is already in the works and there are several open Julia issues about the work needed. One of the main problems is that ARM support in LLVM and OpenBLAS is not very good and we need time for these libraries to mature in this direction. Another is that systems with ARM chips are much less powerful than their x86 counterparts. Building Julia on Raspberry Pi currently takes 12-16 hours and tends to run out of memory.</cite>

      * <cite> Real time control is difficult in a garbage-collected language because you cannot predict when the garbage collector will decide to act. This is also a problem in Java. There is an open issue on implementing better garbage collection algorithms in Julia and we are trying to arrange for a student to work full time on this problem.</cite>

    3. Funding source for JuliaQuantum. This time, we have poster presentations in a professional workshop for a project under our org. All the expenses are out of the presenter’s pocket. In the future, we might want to collect some funds to cover those kind of expenses in need to encourage profound activities in our org. 

    4. Bring our projects to more university students and researchers by posting tutorials, blogs and other multimedia demos for teaching and studying in quantum science. We might also be ready to kick start a university/institution program to establish loyal developer and user groups globally, and establish collaborations with various institutes for teaching, utilities and developing. Call for volunteers from now. 

    5. Stabilize a sustainable mechanism of planning, decision-making and executing for our org. May need to extend our core member group to handle much more complicated situations and activities for the future.   

Ideal timeline:

* Before Middle of Feb, 2015: Finishing the main framework of QuBase.jl and associated projects. 

* Feb 19, 2015: Present our work in the 17th SQuInT workshop.

* Before June or so, 2015: Complete the QuBase.jl and registered as an official Julia community package. Gain enough experiences on interfacing with other packages. Get enough working examples and tutorials ready for the next phase. Have a few building blocks for quantum dynamics solvers ready for the next phase. Discuss with the steering team of JuliaQuantum for the future work of the organization. 
