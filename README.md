<h2> Hi, I'm Fuad Hasan! <img src="https://media.giphy.com/media/8wVNTWVBz7FWq1dXb4/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExY291aHNlemdlbGJkb3pxNTNtbGt6YWV5dGw5M2g0OGJmcmtvYWVuYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/FESR3LbaChnOooURd1/source.gif" width="150">
<p><em>Graduate Student at <a href="https://www.rpi.edu">Rensselaer Polytechnic Institute</br> 
</em></p>

[![Linkedin: fuad-hasibul-hasan](https://img.shields.io/badge/LinkedIn-Connect-blue?style=social&logo=linkedin)](https://www.linkedin.com/in/fuad-hasibul-hasan/)
[![GitHub Fuad-HH](https://img.shields.io/github/followers/Fuad-HH)](https://github.com/Fuad-HH)
[![Email: fuad_h_hasan](https://img.shields.io/badge/Gmail-Send_an_Email-blue?style=social&logo=gmail)](mailto:fuadhhasan.for@gmail.com)

#### A little more about me...

```cpp
#include <grow_up.hpp>

using GrowUP::read_more_books;
using GrowUP::talk_a_lot;
using GrowUP::code_more;
using GrowUP::travel_more;
using GrowUP::be_more_awesome;

struct fuad{
    const std::string name = "Fuad Hasan";
    const std::string major = "Nuclear Engineering";
    std::vector<std::string> languages = {"C++", "Python"};
    std::vector<std::string> hobbies = {"Reading", "Coding", "Traveling", "Cooking"};
    std::vector<std::string> interests = {"Scientific Computation", 
                                        "Nuclear Fission and Fusion", "Radiation Interactions"};
};

fuad get_upgrade(fuad current_me){
    fuad new_me;
    code_more(current_me);
    read_more_books(current_me);
    talk_a_lot(current_me);
    travel_more(current_me);
    be_more_awesome(current_me);
  
    return new_me;
}

int main(int argc, char* argv[])
{
    fuad new_me = get_upgrade();
    return 0;
}
```
---
