<div align="center">

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>


```ruby
class Danilo
  attr_reader :age, :role, :company, :years_in_tech
  
  def initialize
    @age = 21
    @role = "Software Engineering Team Leader"
    @company = "Bee2Solutions"
    @years_in_tech = 3
    @started_at = 18
  end
  
  def stack
    {
      languages: ["Ruby", "TypeScript"],
      frameworks: ["Rails"],
      focus: ["Backend Architecture", "Database Management"]
    }
  end
  
  def side_projects
    [
      "Writing children's literature",
      "Composing indie folk songs",
      "Studying cachalots and marine life"
    ]
  end
  
  def currently_working_on
    [
      "Leading backend teams at #{@company}",
      "Optimizing database performance",
      "Building scalable server architectures"
    ]
  end
  
  def fun_fact
    "Cachalots (sperm whales) can dive over 2km deep and hold their breath for 90 minutes"
  end
  
  def open_to
    ["Backend opportunities", "Tech discussions", "Music collabs", "Whale facts"]
  end
end

# => Let's connect!
```