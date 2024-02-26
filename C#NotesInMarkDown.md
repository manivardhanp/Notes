1. **Advantages of OOPS:**
   - Reuse of code through inheritance.
   - Flexibility through polymorphism.
   - The principle of data hiding/Encapsulation helps the programmers to build secure programs.
   - OOPS system can be easily upgraded from small to large system.
   - Modularity for easier troubleshooting. (Modularity means when you divide the application into different small modules, you easily identify in which class you have to look for a particular thing, exception or errors or classes).

2. **Disadvantages of OOPS:**
   - It is not suitable for small applications.

3. **Types of inheritance:**
   - Single inheritance	
   - Multiple inheritance
   - Multilevel inheritance
   - Hierarchical inheritance

   **Single inheritance:**
   ```csharp
   class BaseClass
   {
       public void Animal()
       {
           Console.WriteLine("Animal");
       }
   }
   
   class ChildClass : BaseClass
   {
       public void Cat()
       {
           Console.WriteLine("Dog");
       }
   }
