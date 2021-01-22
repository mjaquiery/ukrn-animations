# Open code - script

###### tags: `MRC` `UKRN` `open code` `Primers` `animation script`

## Intro 
Many researchers use software in their work.
When this software is shared freely and openly, people use, check, and contribute to improving it.
Open code is software that has an open license, allowing people to inspect the code behind it. 
Many open licenses allow the code to be modified and shared, too.

## Why
Researchers often use software to collect raw data, and to turn raw data into interpretable results.
Although researchers try to describe this process carefully when they publish a study, there is never room to describe everything exactly.
By publishing software as open code, researchers can show exactly how their raw data lead to the results they report.
Other researchers can then check to make sure there aren't errors in the code which affect the results, and check that the results reported in the paper match the output from the code.

There are other advantages to publishing open code, too: the publication acts as a backup so code doesn't get lost when moving labs; and it allows communities and standards to form which help improve the software.
Many important pieces of software used by researchers every day are built by communities contributing to open code, including the Firefox web browser and the Python and R programming languages. 
> It would be good to have some bio/medsci-specific examples here. There will be some major workflow components that are FOSS [name=Matt Jaquiery]

## How
There are two steps researchers need to take to make their code open and accessible.
The first is to choose a license which tells people what they can and can't do with your code. 
Common open code licenses include the MIT license, which allows people to do more or less anything with your code, and the GNU General Public License v3 which allows people to do more or less anything as long as any software which uses your code is released under the GNU GPL.
For documentation, data, materials and procedures, and code that doesn't need to be compiled, like analysis scripts, the Creative Commons family of licenses offer an easy-to-understand range of permissions. 
You can find more help on licensing at ChooseALicense.com.
You can only apply a license to code that you own, so you need to check with your employer whether the code you write is yours or theirs.
If it belongs to them, you must ask their permission before you release the code under a license.

The second step is to put your code somewhere where other researchers can find it.
Many researchers use version control platforms like GitHub.com to share code.
These platforms make it possible to find code, and also help to organise collaborations by allowing people to work on individual copies of the code and send patches to one another.

## Worries
Many researchers worry about sharing their code. 
They are concerned that other people will find mistakes in their code, or that their code is very messy and difficult to follow.
These worries are understandable, because it's scary to think that other people can look over your work in such detail, but researchers should share their code anyway.

There are almost always mistakes in code, and finding those mistakes makes the code better. 
When those mistakes affect results, it's even _more_ important to find them, because otherwise we continue to believe things that aren't true. 
It is difficult to accept when we find results are caused by mistakes, but it does not harm the careers of scientists who can accept these things when they happen.

Most researchers are not also professional software developers, and so most researchers write code which is messy, poorly organised, and fragile.
There are many benefits of writing good code: it is easier to understand and maintain, less likely to contain mistakes, and easier for others to build on and adapt.
Researchers who can take the time to improve their coding skills should do so.
But researchers should share their code whether or not it is clean and efficient.
Because messy code is difficult to understand, it is even more important to allow as many people as possible to inspect and run the code so that they can find and help fix mistakes.

## Benefits
Sharing code also has benefits for individual researchers sharing the code because it can be cited as a research output. 
For example, Zenodo.org integrates with GitHub.com to provide Digital Object Identifiers (or 'DOI's) for open code.
> This could be wrapped into the 'how' bit about GitHub? [name=Matt Jaquiery]

## Conclusion
Sharing code openly helps to make the software that supports our research better. 
It allows people to work together to ensure that code does what it is supposed to.
It allows people to work together to make software that is more reliable, easier to access, and easier to use.
It allows people to build on each other's work to do things no one could do alone - it is the scientific approach to knowledge applied to code.

---

Links
* https://choosealicense.com/
* https://github.com/
* https://guides.github.com/activities/citable-code/

* https://ukrn.org/primers/
