# Software Inc. Snippets for VS Code

[![GitHub release](https://img.shields.io/badge/GitHub%20Release-V%201.0-ff5100.svg?style=for-the-badge)](https://github.com/Nicholas-LeClair/softinc-snippets/releases)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20MarketPlace-V%201.0-246ee5.svg?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=Nickal.softinc-snippets)
[![MIT License](https://img.shields.io/badge/License-MIT-e52424.svg?style=for-the-badge)](https://github.com/Nicholas-LeClair/softinc-snippets/blob/master/LICENSE)

![DemoGif](https://github.com/Nicholas-LeClair/softinc-snippets/blob/master/videos/README.gif)

#### Please refer to the mod documentation for a full understanding: https://softwareinc.coredumping.com/wiki/index.php/Modding

## Directions
Just start typing the name of the tag you want and it should pop up with options. Example to use the ```<Name></Name>``` simply type Name and it will correct to ```<Name></Name>```.

## Tags
* SoftwareType
* Name
* Delete
* Category
* Categories
* Description
* Unlock
* Random
* Popularity
* Retention
* Iterative
* OSSpecific
* OneClient
* InHouse
* NameGenerator
* OSLimit
* IdealPrice
* Features
* Feature
* ArtCategory
* DevTime
* Innovation
* Usability
* Stability
* CodeArt
* Server
* Dependency
* SoftwareCategory
* Popularity
* TimeScale
* Retention
* IdealPrice
* Iterative
* CompanyType
* Specilization
* Force
* PerYear
* Min
* Max
* Types
* NameGen
* PersonalityGraph
* Personalities
* Incompatibilites
* Incompatible
* Personality
* WorkLean
* Social
* LazyStress
* Relationships
* Relation

## Commands
* New Software Type 

``` 
<SoftwareType>
    <Name></Name>
    <Unlock></Unlock>
    <Category></Category>
    <Description></Description>
    <Random></Random>

    <Categories>
        <Category Name=''>
            <Description></Description>
            <Unlock></Unlock>
            <Popularity></Popularity>
            <Retention></Retention>
            <TimeScale></TimeScale>
            <Iterative></Iterative>
        </Category>
    </Categories>

    <OSSpecific></OSSpecific>
    <OneClient></OneClient>
    <InHouse></InHouse>
    <NameGenerator></NameGenerator>

   <Features>
       <Feature Forced=''>
            <Name></Name>
            <Category></Category>
            <Description></Description>
            <DevTime></DevTime>
            <Innovation></Innovation>
            <Usability></Usability>
            <Stability></Stability>
            <CodeArt></CodeArt>
        </Feature>
   </Features>

</SoftwareType> 
```
* New Feature
```
<Feature>
    <Name></Name>
    <Category></Category>
    <Description></Description>
    <DevTime></DevTime>
    <Innovation></Innovation>
    <Usability></Usability>
    <Stability></Stability>
    <CodeArt></CodeArt>
</Feature>
```
* New Personality Graph
```
<PersonalityGraph>
    <Personalities>
        <Personality>
            <Name></Name>
            <WorkLean></WorkLean>
            <Social></Social>
            <LazyStress></LazyStress>
            <Relationships>
                <Relation></Relation>
            </Relationships>
         <Personality>
    </Personalities>

    <Incompatibilities>
        <Incompatible>
            <Personality></Personality>
        </Incompatible>
    </Incompatibilities>

</PersonalityGraph>
```
* New Personality
```
<Personality>
    <Name></Name>
    <WorkLean></WorkLean>
    <Social></Social>
    <LazyStress></LazyStress>
    <Relationships>
        <Relation></Relation>
    </Relationships>
<Personality>
```
* New Incompatibilities
```
<Incompatibilities>
    <Incompatible>
        <Personality></Personality>
    </Incompatible>
</Incompatibilities>
```
* New CompanyType
```
<CompanyType>
    <Specialization></Specialization>
    <PerYear></PerYear>
    <Min></Min>
    <Max></Max>
    <Types>
        <Type Software=''></Type>
    </Types>
</CompanyType>
```