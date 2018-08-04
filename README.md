# Software Inc. Snippets for VS Code

[![GitHub release](https://img.shields.io/badge/GitHub%20Release-V%201.1-ff5100.svg?style=for-the-badge)](https://github.com/Nicholas-LeClair/softinc-snippets/releases)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20MarketPlace-V%201.1-246ee5.svg?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=Nickal.softinc-snippets)
[![Patch](https://img.shields.io/badge/Patch-0-246ee5.svg?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=Nickal.softinc-snippets)
[![MIT License](https://img.shields.io/badge/License-MIT-e52424.svg?style=for-the-badge)](https://github.com/Nicholas-LeClair/softinc-snippets/blob/master/LICENSE)

![DemoGif](https://raw.githubusercontent.com/Nicholas-LeClair/softinc-snippets/master/videos/README.gif)

#### Please refer to the mod documentation for a full understanding:     https://softwareinc.coredumping.com/wiki/index.php/Modding

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
* Root
* Models
* Model
* File
* Position
* Rotation
* Scale
* InteractionPoints
* InteractionPoint
* Animation
* Child
* Furniture
* BuildBoundary
* NavBoundary
* Height1
* Height2
* Upgradable
* UpgradePrice
* Server
* Power
* BoxCollider
* Center
* Size
* Base
* Bump
* Extra
* Skirting
* FloorType
* CoolPack

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
        <Category Name=""">
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
       <Feature Forced=""">
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
* New Company Type
```
<CompanyType>
    <Specialization></Specialization>
    <PerYear></PerYear>
    <Min></Min>
    <Max></Max>
    <Types>
        <Type Software="""></Type>
    </Types>
</CompanyType>
```
* New Furniture Type
```
<Root Base="" Thumbnail="" UpgradeFrom="">
<Models>
   <Model>
      <File>BigServerRack.obj</File>
      <Position>0,0,0</Position>
      <Rotation>0,0,0</Rotation>
      <Scale>1,1,1</Scale>
   </Model>
</Models>
<InteractionPoints>
   <InteractionPoint>
      <Name>Repair</Name>
      <Position>0,0,0</Position>
      <Rotation>0,0,0</Rotation>
      <Animation>Repair</Animation>
      <Child>0</Child>
   </InteractionPoint>
   <InteractionPoint>
      <Name>Repair</Name>
      <Position>0,0,0</Position>
      <Rotation>0,0,0</Rotation>
      <Animation>Repair</Animation>
      <Child>0</Child>
   </InteractionPoint>
</InteractionPoints>
<Furniture>
   <Cost>0</Cost>
   <Wattage>0</Wattage>
   <Noisiness>0</Noisiness>
   <UnlockYear>0</UnlockYear>
   <ButtonDescription></ButtonDescription>
   <ColorPrimaryDefault>0,0,0,0</ColorPrimaryDefault>
   <PrimaryColorName>0,0,0,0</PrimaryColorName>
   <ColorSecondaryDefault>0,0,0,0</ColorSecondaryDefault>
   <ColorTertiaryDefault>0,0,0,0</ColorTertiaryDefault>
   <ColorSecondaryEnabled></ColorSecondaryEnabled>
   <ColorTertiaryEnabled></ColorTertiaryEnabled>
   <ForceColorSecondary></ForceColorSecondary>
   <ForceColorTertiary></ForceColorTertiary>
   <PrimaryColorName></PrimaryColorName>
   <SecondaryColorName></SecondaryColorName>
   <TertiaryColorName></TertiaryColorName>
   <BuildBoundary></BuildBoundary>
   <NavBoundary></NavBoundary>
   <Height1>0</Height1>
   <Height2>0</Height2>
   <OnXEdge>True</OnXEdge>
</Furniture>
<Upgradable>
   <UpgradePrice>0</UpgradePrice>
</Upgradable>
<Server>
   <Power>0</Power>
</Server>
<BoxCollider>
   <center>0,0,0</center>
<size>0,0,0,</size>
</BoxCollider>
</Root>
```
* New Model
```
<Model>
   <File></File>
   <Position></Position>
   <Rotation></Rotation>
   <Scale></Scale>
</Model>
```
* New Interaction Point
```
<InteractionPoint>
   <Name></Name>
   <Position></Position>
   <Rotation></Rotation>
   <Animation></Animation>
   <Child></Child>
</InteractionPoint>
```
* New Furniture
```
<Furniture>
   <Cost></Cost>
   <Wattage></Wattage>
   <Noisiness></Noisiness>
   <UnlockYear></UnlockYear>
   <ButtonDescription></ButtonDescription>
   <ColorPrimaryDefault></ColorPrimaryDefault>
   <PrimaryColorName></PrimaryColorName>
   <ColorSecondaryDefault></ColorSecondaryDefault>
   <ColorTertiaryDefault></ColorTertiaryDefault>
   <ColorSecondaryEnabled></ColorSecondaryEnabled>
   <ColorTertiaryEnabled></ColorTertiaryEnabled>
   <ForceColorSecondary></ForceColorSecondary>
   <ForceColorTertiary></ForceColorTertiary>
   <PrimaryColorName></PrimaryColorName>
   <SecondaryColorName></SecondaryColorName>
   <TertiaryColorName></TertiaryColorName>
   <BuildBoundary></BuildBoundary>
   <NavBoundary></NavBoundary>
   <Height1></Height1>
   <Height2></Height2>
   <OnXEdge></OnXEdge>
</Furniture>
```
* New Material Type
```
<CoolPack>
   <EnterNameHere>
      <Category></Category>
      <Base></Base>
      <Bump></Bump>
      <Extra></Extra>
      <Skirting></Skirting>
   </EnterNameHere>
</CoolPack>
```
* New Material 
```
<EnterNameHere>
   <Category></Category>
   <Base></Base>
   <Bump></Bump>
   <Extra></Extra>
   <Skirting></Skirting>
</EnterNameHere>
```