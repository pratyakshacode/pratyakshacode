<h3> public class MyDescription </h3> {

      public String Name, gitHubId, Education, College, Email;
      public String [] skills;
      
      
      public MyDescription(){
      
            this.Name ="Pratyaksha Verma";
            this.gitHubId = "@pratyakshacode";
            this.Education ="Btech Computer Science and Engineering with an average of 9.0 cgpa";
            this.College = "Noida Institute of Engineering and Technology, Greater Noida";
            this.Email = "pratyakshaverma2018@gmail.com;
     }
     
     public static void main(String [] args) {
     
     MyDescription desc = new MyDescription();
     
     desc.skills = {"C++ programming", "Java" , "MERN Stack", "Firebase"};
     System.out.println("👋 Hi, I’m " + desc.Name + " - " + desc.gitHubId);
     System.out.println("🌱 I’m Currently pursuing " + desc.Education + " at " + desc.College);
     System.out.println("👀 My skills includes ");
     
     for(var skill : desc.skills){
        System.out.println(skill);
     }
     
     System.out.println("📫 How to reach me Email id -> " + desc.Email);
     
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






