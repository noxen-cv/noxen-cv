``` cpp
static int careerPathcount = 0;
int skillsInDev, skillsinFilm;
int& levelExpDev  = skillsinDev;
int& levelExpFIlm = skillsinFilm;

do (Stable job = true) {							// While I still have a stable job
    Hobbies();								        // Do my hobbies
    learnDev();
    learnFilm();
    if (skillsInDev == 5 || skillsInFilm == 5) {    // If I reached a point of what I learned
    levelExpDev = 0; levelExpFilm = 0;		        // reset to 0, since we never stop learning
    careerPathcount += 1;					        // append careerPath opportunity to 1
    }
    IncreasePassiveIncome();                        // while also making money in passive income
} while ( PassiveIncomeSuccess == false ) {}        // do all of this while not successful yet


```
