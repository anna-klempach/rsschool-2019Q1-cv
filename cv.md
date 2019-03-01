# **CURRICULUM VITAE**

## *Hanna Klempach*

## Personal details
*Date of birth* : February 20, 1987

*Address*: 25-187, Slobodskaya str. , Minsk, Belarus


## Contacts
*Phone number*: (+37533) 637-63-60

*E-mail*: klempach.teaching@gmail.com

*Skype*: live:a4205bf5655a7ee5

## Summary

My name is Hanna, I am 32. I am married with one child, aged 2. I graduated from Minsk State Linguistic University in 2010, where I majored in modern foreign languages, specifically English and Italian. I have a seven-year working experience in education as a teacher of English. Although I found great inspiration in my previous job, I would like to try something more challenging and rewarding, that is why at the moment I am studying software engineering at BSUIR. 

I am eager to become a specialist in software development. I am convinced that I have all the necessary skills to become a proficient specialist and a good employee. I am hard-working and quick-minded, able to work in stressful environment (that is what my life was like for 7 working years) and as part of a team. What is more, I am good at time management, and my colleagues and management at previous woking places considered me a very reliable, skillful and promising specialist. 

I am a very motivated and independent learner, and I am quick at acquiring new skills and knowledge. I have always been a good student and my skills in learning are improving with time. I believe, that self-education is the main force in self-improvement and professional growth. As you can see from my CV, I have spent quite a lot of time educating myself via online courses and I am not going to stop.

So, why am I here? I have always been interested in IT. When at university, I specialized in applied linguistics. I enjoyed it immensely and I intended to continue work in this sphere, but due to family matters I did not have a chance to achieve my goal. At the moment I find great enjoyment in doing challenging tasks in the sphere which I have always wanted to work in.

## Skills

*Javascript / HTML / CSS* : intermediate;

*C / C++*: intermediate;

*Windows OS*: basic;

Basic knowledge of *architecture of operation systems* and *technical arrangement of information systems*.

## Examples of code

### JavaScript:

function searchCurrentValue(array, index) {

    for (let j = 0; j < array[index].possibleVariants.length; j++) {
        if (checkElements(array, index, array[index].possibleVariants[j]) == true) {
            array[index].currentValue = array[index].possibleVariants[j];
            if (index === array.length - 1) {
                return array;
            } else {
                if (searchCurrentValue(array, index + 1) == false) {
                    if (j < array[index].possibleVariants.length - 1) {
                        continue;
                    } else {
                        array[index].currentValue = 0;
                        return false;
                    }
                } else {
                    return array;
                }
            }
        } else {
            if (j === array[index].possibleVariants.length - 1) {
                array[index].currentValue = 0;
                return false;
            } else {
                continue;
            }
        }
    }
}

## Educational background

### Higher education

Time period | Educational Institution, faculty | Major | Qualification(s)
----------- | -------------------------------- | ----- | ---------------- 
*2005-2010* | Minsk State Linguistic University, English faculty | Modern foreign languages (teaching) | Linguist. Teacher of English and Italian. Specialist in applied linguistics.
*2018 - present* | Institute of Information Technologies (Belarusian State University of Informatics and Radioelectronics), Refresher and Retraining Department (distance learning) | Software of information systems | software engineer.  

### Online courses

#### codecadamy.com (HannaKlempach2206764908): 

* Introduction to HTML;
* Learn CSS.

#### htmalacedemy.ru (id861275):

* HTML basics;
* CSS basics; 
* JavaScript basics;
* Construction of grids;
* Decorative effects;
* Text processing;
* Workshops;
* JavaScript in a browser;
* SVG;
* Dynamic effects;
* Preprocessor LESS.

## Foreign languages

* Proficient in *English*;

* *Italian*: basic.

## Employment history

Time period | Place of work, position
----------- | -----------------------
*2010-2011* | Minsk State Linguistic University, Institute for Advanced Studies and Retraining, trainee teacher of English;
*2011-2015* | School #1, Bobruisk, teacher of English;
*2013-2017* | StepbyStep (later RightStart) school, teacher of English;
*2015-present* | Gymnasium #2, Bobruisk,  teacher of English (currently on maternity leave).