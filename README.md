<h3> public class MyDescription <h3> {

      public String Name, gitHubId, Education, College, Email;
      public String [] skills;
      
      
      public MyDescription(Name, gitHubId, Education, College, Email){
            this.Name = Name;
            this.gitHubId = gitHubId;
            this.Education = Education;
            this.College = College;
            this.Email = Email;
     }
     
     public static void main(String [] args) {
     
     MyDescription desc = new MyDescription("Pratyaksha Verma" , "@pratyakshacode", "Btech Computer Science and Engineering", "Noida Institute of Engineering and Technology, Greater Noida", "pratyakshaverma2018@gmail.com");
     
     desc.skills = {"C++ programming", "Java" , "MERN Stack", "Firebase"};
     System.out.println("👋 Hi, I’m " + desc.Name + " - " + desc.gitHubId);
     System.out.println("🌱 I’m Currently pursuing " + desc.Education + " at " + desc.College);
     System.out.println("👀 My skills includes ");
     
     for(var skill : desc.skills){
        System.out.println(skill);
     }
     
     System.out.println("📫 How to reach me " + desc.Email);
     
    }}
 
Output ->

- <h4>👋 Hi, I’m  </h4> <h3> Pratyaksha Verma - @pratyakshacode </h3>
- <h4> 🌱 I’m Currently pursuing </h4> <h3> B.tech in Computer Science And Engineering with an average of 9.0 cgpa; </h3> <br>
- <h4> My skills includes </h4>
- <h3> C++ </h3>
- <h3> Java </h3>
- <h3> MERN stack </h3>
- <h3> Firebase </h3>
- <h3>📫 How to reach me </h3> Email id -> pratyakshaverma2018@gmail.com;






