### 0.4.0+d2b66f4 (Released 2023-10-19)
* Additions:
    * [[#226c3eb](https://github.com/CSBiology/OBO.NET/commit/226c3eb371b537d8799d3c44a01f9e064062ceda)] Investigate current synonym functionalities
    * [[#5c666c3](https://github.com/CSBiology/OBO.NET/commit/5c666c3351513d04d29e2f26ff825a9d57bcce59)] Pinpoint current dependencies for safety reasons
    * [[#d1db10e](https://github.com/CSBiology/OBO.NET/commit/d1db10e26d3fc2be337ae702e3f8b733ffad5ca2)] Add F#Aux dependency
    * [[#3aec348](https://github.com/CSBiology/OBO.NET/commit/3aec348e202af19fd13cdb2d54300d8317298bd0)] Add functions to get synonyms (WIP)
    * [[#812320a](https://github.com/CSBiology/OBO.NET/commit/812320abe806f91b3282893a508a2f0b51f0ad55)] Add synonym unit tests
    * [[#b7e80c1](https://github.com/CSBiology/OBO.NET/commit/b7e80c1514e9294541b08704a07b8c6e13dddd6c)] Add unit tests for try synonyms
    * [[#d02c71e](https://github.com/CSBiology/OBO.NET/commit/d02c71efe549e1913ad9cf232ebf4dc06ee30e70)] Pimp README docu
    * [[#ba1ebc0](https://github.com/CSBiology/OBO.NET/commit/ba1ebc09b2b34679e2a7ee4be2c82469ac3348c0)] Change output type of synonym function
    * [[#04ad89c](https://github.com/CSBiology/OBO.NET/commit/04ad89c38efd39ef5ee65a30ea7d3eaa8a212b6a)] Rename into OBO.NET
    * [[#6748ae0](https://github.com/CSBiology/OBO.NET/commit/6748ae0a14647ad5d787f9d86be9b4bec69dba10)] Rename projects in build project info
    * [[#b93d13f](https://github.com/CSBiology/OBO.NET/commit/b93d13f6e9234f7c207a4d269058ab218a59d8fd)] Rename folder
    * [[#a1a02da](https://github.com/CSBiology/OBO.NET/commit/a1a02da3b38bce844a6bd3a89fa4ed189929a5ab)] Change folder name
    * [[#2506508](https://github.com/CSBiology/OBO.NET/commit/2506508760c163f4baaf4de5c0212e2a15193ea6)] Change folder dir in sln file
    * [[#fc65bc7](https://github.com/CSBiology/OBO.NET/commit/fc65bc7816588c84ac739000be63f13c98706385)] Change folder dir in tests project file

### 0.3.0+da71d21 (Released 2023-8-21)
* Additions:
    * [[#3a8ac9a](https://github.com/CSBiology/FsOboParser/commit/3a8ac9abbc5a2923fa4f278b6168eb7ccf3dcbee)] Add unit tests for getting `is_a`s & TermRelations
    * [[#a870ef3](https://github.com/CSBiology/FsOboParser/commit/a870ef30cac09b59615f3a6a846ac70063a859e1)] Add functions to get TermRelations and `is_a`s
    * [[#45fb8b5](https://github.com/CSBiology/FsOboParser/commit/45fb8b51aff7ceb64a3c5195a1eac8e1267c96f1)] Add TermRelation type
    * [[#b8acba0](https://github.com/CSBiology/FsOboParser/commit/b8acba095848dfe9fdbed8a923399334a1afc8f7)] Revert "Update Fake.Extensions dependency @ build proj"
    * [[#161a053](https://github.com/CSBiology/FsOboParser/commit/161a053c7b93952d95c4b3abe6bb9419a444a1d0)] Update Fake.Extensions dependency @ build proj

### 0.2.0+afd7c0a (Released 2023-8-19)
* Additions:
    * [[#dc6fd13](https://github.com/CSBiology/FsOboParser/commit/dc6fd1353d84ff8c72fde5bb41dc126a70c5fb8e)] various repo structure improvements
    * [[#244881c](https://github.com/CSBiology/FsOboParser/commit/244881c7b7a5d6ef6bddcd52965022ba4fa4f05a)] add source link and symbols package
    * [[#2c5aaae](https://github.com/CSBiology/FsOboParser/commit/2c5aaae4b332bad0aec40ec61bb231531720782f)] Update Readme's minidocs
    * [[#a97d033](https://github.com/CSBiology/FsOboParser/commit/a97d03339beb3f59600013049333adb2c8898244)] Give alternative result into Readme's minidocs
    * [[#184c20a](https://github.com/CSBiology/FsOboParser/commit/184c20aaa73fa4b82e78bb77f5f332c0a568d5f8)] Add `OboEntry` type
    * [[#16a9a6e](https://github.com/CSBiology/FsOboParser/commit/16a9a6ec97c21b1abe0f6e754888aa6090099464)] Add OboEntry functionality into OboOntology
    * [[#eb6dca1](https://github.com/CSBiology/FsOboParser/commit/eb6dca1188e2e7718642ed847bf0d21971ad0ca5)] Move OboEntries into own module for clarity reasons
    * [[#28b8da1](https://github.com/CSBiology/FsOboParser/commit/28b8da193f6e4ab7a8f6c52af8d355c5ee64e375)] Add `fromOboEntries` function to OboOntology type
    * [[#e9c6c34](https://github.com/CSBiology/FsOboParser/commit/e9c6c34319b35911a6d1fc750e63d99f5b805c50)] ReAdd original fromFile method of OboOntology due to performance reasons
    * [[#63512c8](https://github.com/CSBiology/FsOboParser/commit/63512c89a04081469126aa4af32901efeb23f55d)] Merge pull request #9 from CSBiology/feature-minimalParser-#5
    * [[#cf856a4](https://github.com/CSBiology/FsOboParser/commit/cf856a4ddd4c3709d434399cf6506a0e0b19caf5)] Add OBO interface (WIP)
    * [[#418452e](https://github.com/CSBiology/FsOboParser/commit/418452e285d10f423a9791cf413e7c26b668f672)] Add some functions to get relationships (WIP)
    * [[#acec96f](https://github.com/CSBiology/FsOboParser/commit/acec96fcc705050816b39f65585e4fc7cbd65ee8)] Revert "Add OBO interface (WIP)"
    * [[#60a185e](https://github.com/CSBiology/FsOboParser/commit/60a185e67996074ef8bdf5993a593db1866b0375)] Finish term relation functions

### 0.1.0+2b6617b (Released 2023-7-25)
* Additions:
    * [[#2b6617b](https://github.com/CSBiology/FsOboParser/commit/2b6617bb1b8c885a141e80d5718a10dae72ce09e)] Add package metadata
    * [[#c7cbd18](https://github.com/CSBiology/FsOboParser/commit/c7cbd183aace54370a2c1d8e3b5b198b14b928c4)] Finish Readme (for now)
    * [[#5c5caa9](https://github.com/CSBiology/FsOboParser/commit/5c5caa93238f5d5ec49c0ccc9d9e17e4ddb4cfcb)] Add creation function for OBO type def
    * [[#989a736](https://github.com/CSBiology/FsOboParser/commit/989a736b593692a79f2b3bbd1ae5b498e66e8339)] Restructure library
    * [[#4553f5c](https://github.com/CSBiology/FsOboParser/commit/4553f5cc693970258f6f2742b5f67c0cc63d7585)] Update Readme with Build tutorial
    * [[#fbcc358](https://github.com/CSBiology/FsOboParser/commit/fbcc358b040f49b8f8ab60d50dacd1ecf3cfd471)] add build project
    * [[#971aa55](https://github.com/CSBiology/FsOboParser/commit/971aa55eb0a527aa4a6b8b8b24facf057dfc1637)] Add test project
    * [[#541fb49](https://github.com/CSBiology/FsOboParser/commit/541fb49b35e34bb9b0eaa1f08f4b2fd625d3bc3d)] Copy and split OboParser into parts
    * [[#a2e0ca0](https://github.com/CSBiology/FsOboParser/commit/a2e0ca045c11ff3774c438ee04f4ff4d5935d135)] Initial commit
* Deletions:
    * [[#3536b6f](https://github.com/CSBiology/FsOboParser/commit/3536b6ff0f6fb1df884e6be912e2b4fc49bc142e)] Delete test method
* Bugfixes:
    * [[#e52af5d](https://github.com/CSBiology/FsOboParser/commit/e52af5d351cad07019beb5c19d1f24858518e7d3)] Fix OBO term creation function
    * [[#cb179a7](https://github.com/CSBiology/FsOboParser/commit/cb179a7ac919b4d610c1eb75314af47027fce67a)] Update Readme, fix some typos, test functions
    * [[#76bbfe8](https://github.com/CSBiology/FsOboParser/commit/76bbfe89b62108d36da5a86130cfa280b79ad865)] Fix some typos, clarify ///-comments
    * [[#79e5a43](https://github.com/CSBiology/FsOboParser/commit/79e5a43fb08dc5bac34581428069e6dffc7b8f70)] Fix critical module bug

### 0.0.0 (Released 2023-7-25)
* Additions:
    * Initial set up for RELEASE_Notes.md

