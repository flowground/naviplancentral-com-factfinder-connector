# ![LOGO](logo.png) Advicent.FactFinderService **flow**ground Connector

## Description

A generated **flow**ground connector for the Advicent.FactFinderService API (version v1).

Generated from: https://api.apis.guru/v2/specs/naviplancentral.com/factfinder/v1/swagger.json<br/>
Generated at: 2019-06-06T16:12:52+03:00

## API Description

An API for accessing the Narrator Fact Finder.

## Authorization

This API does not require authorization.

## Actions

### Description: This operation retrieves all Account Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Account Types including id and type description.

*Tags:* `AccountTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Account Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves all Account Types for the specified id.<br /><br/>
>               Purpose: Provides access to the Account Types including id and type description.

*Tags:* `AccountTypes`

#### Input Parameters
* `id` - _required_ - The ID of Account Type used to retreive the Account Type information

### Description: This operation retrieves all Accounts for the specified Fact Finder ID and/or external source ID.<br /><br/>
>               Purpose: Provides access to the Account information including description and market value.

*Tags:* `Accounts`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Accounts
* `externalSourceId` - _optional_ - The external ID used to filter Accounts

### Description: The operation creates an Account.<br /><br/>
>               Purpose: Allows for creation of Accounts on a Fact Finder.

*Tags:* `Accounts`

### Description: This operation retrieves a single Account Holding for the specified Account Holding ID and Account ID.<br /><br/>
>               Purpose: Provides access to the Account Holding information including description and market value.

*Tags:* `Accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the Account used to retreive the Account Holding data
* `id` - _required_ - The ID of the Account Holding used to retreive the Account Holding data

### Description: The operation removes an Account tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of an Account from a Fact Finder.

*Tags:* `Accounts`

#### Input Parameters
* `id` - _required_ - The Account ID used to identify which Account to remove

### Description: This operation retrieves a single Account for the specified Account ID.<br /><br/>
>               Purpose: Provides access to the Account information including description and market value.

*Tags:* `Accounts`

#### Input Parameters
* `id` - _required_ - The ID of the Account used to retreive the Account data

### Description: The operation updates an Account.<br /><br/>
>               Purpose: Allows for complete replacement of an Account on a Fact Finder.

*Tags:* `Accounts`

#### Input Parameters
* `id` - _required_ - The existing Account ID used to identify which Account to update

### Description: This operation submits the Fact Finder data to an external system.<br /><br/>
>               Purpose: Allows Fact Finder data to be persisted in another system for that system's consumption and use.

*Tags:* `Clients`

### Description: This operation retrieves all Critical Illness Insurance Policies for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Critical Illness Insurance Policies including description and policy type.

*Tags:* `CriticalIllnessInsurancePolicies`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Critical Illness Insurance Policies

### Description: The operation creates a Critical Illness Insurance Policy.<br /><br/>
>               Purpose: Allows for creation of Critical Illness Insurance Policies on a Fact Finder.

*Tags:* `CriticalIllnessInsurancePolicies`

### Description: The operation removes a Critical Illness Insurance Policy tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Critical Illness Insurance Policy from a Fact Finder.

*Tags:* `CriticalIllnessInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The Critical Illness Insurance Policy ID used to identify which Critical Illness Insurance Policy to remove

### Description: This operation retrieves a single Critical Illness Insurance Policy for the specified Critical Illness Insurance Policy ID.<br /><br/>
>               Purpose: Provides access to the Critical Illness Insurance Policy including description and policy type.

*Tags:* `CriticalIllnessInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The ID of the Critical Illness Insurance Policy used to retreive the Critical Illness Insurance Policy

### Description: The operation updates a Critical Illness Insurance Policy.<br /><br/>
>               Purpose: Allows for complete replacement of a Critical Illness Insurance Policy on a Fact Finder.

*Tags:* `CriticalIllnessInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The existing Critical Illness Insurance Policy ID used to identify which Critical Illness Insurance Policy to update

### Description: This operation retrieves all Critical Illness Insurance Policy Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Critical Illness Insurance Policy Types including id and type description.

*Tags:* `CriticalIllnessInsurancePolicyTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Critical Illness Insurance Policy Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Critical Illness Insurance Policy Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Critical Illness Insurance Policy Types including id and type description.

*Tags:* `CriticalIllnessInsurancePolicyTypes`

#### Input Parameters
* `id` - _required_ - The ID of Critical Illness Insurance Policy Type used to retreive the Critical Illness Insurance Policy Type information

### Description: This operation retrieves all Defined Benefit Pensions for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Defined Benefit Pensions including description and start date.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Defined Benefit Pensions

### Description: The operation creates a Defined Benefit Pension.<br /><br/>
>               Purpose: Allows for creation of Defined Benefit Pensions on a Fact Finder.

*Tags:* `DefinedBenefitPensions`

### Description: The operation removes a Defined Benefit Pension tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Defined Benefit Pension from a Fact Finder.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `id` - _required_ - The Defined Benefit Pension ID used to identify which Defined Benefit Pension to remove

### Description: This operation retrieves a single Defined Benefit Pension for the specified Defined Benefit Pension ID.<br /><br/>
>               Purpose: Provides access to the Defined Benefit Pension including description and start date.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `id` - _required_ - The ID of the Defined Benefit Pension used to retreive the Defined Benefit Pension

### Description: The operation updates a Defined Benefit Pension.<br /><br/>
>               Purpose: Allows for complete replacement of a Defined Benefit Pension on a Fact Finder.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `id` - _required_ - The existing Defined Benefit Pension ID used to identify which Defined Benefit Pension to update

### Description: This operation retrieves all Demographic information for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Demographic information including city and state.

*Tags:* `Demographics`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Demographic information

### Description: The operation creates Demographic information.<br /><br/>
>               Purpose: Allows for creation of Demographic information on a Fact Finder.

*Tags:* `Demographics`

### Description: This operation retrieves all Dependents for the specified Demographic information ID.<br /><br/>
>               Purpose: Provides access to the Dependents including first and last name.

*Tags:* `Demographics`

#### Input Parameters
* `demographicId` - _required_ - The ID of the Demographic information used to retrieve Dependents

### Description: The operation creates a Dependent.<br /><br/>
>               Purpose: Allows for creation of Dependents on a Fact Finder.

*Tags:* `Demographics`

#### Input Parameters
* `demographicId` - _required_ - The ID of the Demographic information to add the Dependent to

### Description: The operation removes a Dependent tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Dependent from a Fact Finder.

*Tags:* `Demographics`

#### Input Parameters
* `demographicId` - _required_ - The ID of the Demographic information used to identify which Dependent to remove
* `id` - _required_ - The Dependent ID used to identify which Dependent to remove

### Description: This operation retrieves a single Dependent for the specified Dependent ID.<br /><br/>
>               Purpose: Provides access to the Dependent including first and last name.

*Tags:* `Demographics`

#### Input Parameters
* `demographicId` - _required_ - The ID of the Demographic information used to retrieve Dependents
* `id` - _required_ - The ID of the Dependent used to retreive the Dependent

### Description: The operation updates a Dependent.<br /><br/>
>               Purpose: Allows for complete replacement of a Dependent on a Fact Finder.

*Tags:* `Demographics`

#### Input Parameters
* `demographicId` - _required_ - The ID of the Demographic information used to identify which Dependent to update
* `id` - _required_ - The existing Dependent ID used to identify which Dependent to update

### Description: This operation retrieves Demographic information for the specified Demographic information ID.<br /><br/>
>               Purpose: Provides access to the Demographic information including city and state.

*Tags:* `Demographics`

#### Input Parameters
* `id` - _required_ - The ID of the Demographic information used to retreive the Demographic information

### Description: The operation updates Demographic information.<br /><br/>
>               Purpose: Allows for complete replacement of Demographic information on a Fact Finder.

*Tags:* `Demographics`

#### Input Parameters
* `id` - _required_ - The existing Demographic information ID used to identify which Demographic information to update

### Description: This operation retrieves all Disability Insurance Policies for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Disability Insurance Policies including description and policy type.

*Tags:* `DisabilityInsurancePolicies`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Disability Insurance Policies

### Description: The operation creates a Disability Insurance Policy.<br /><br/>
>               Purpose: Allows for creation of Disability Insurance Policies on a Fact Finder.

*Tags:* `DisabilityInsurancePolicies`

### Description: The operation removes a Disability Insurance Policy tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Disability Insurance Policy from a Fact Finder.

*Tags:* `DisabilityInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The Disability Insurance Policy ID used to identify which Disability Insurance Policy to remove

### Description: This operation retrieves a single Disability Insurance Policy for the specified Disability Insurance Policy ID.<br /><br/>
>               Purpose: Provides access to the Disability Insurance Policy including description and policy type.

*Tags:* `DisabilityInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The ID of the Disability Insurance Policy used to retreive the Disability Insurance Policy

### Description: The operation updates a Disability Insurance Policy.<br /><br/>
>               Purpose: Allows for complete replacement of a Disability Insurance Policy on a Fact Finder.

*Tags:* `DisabilityInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The existing Disability Insurance Policy ID used to identify which Disability Insurance Policy to update

### Description: This operation retrieves all Disability Insurance Policy Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Disability Insurance Policy Types including id and type description.

*Tags:* `DisabilityInsurancePolicyTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Disability Insurance Policy Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves all Disability Insurance Policy Types for the specified id.<br /><br/>
>               Purpose: Provides access to the Disability Insurance Policy Types including id and type description.

*Tags:* `DisabilityInsurancePolicyTypes`

#### Input Parameters
* `id` - _required_ - The ID of Disability Insurance Policy Type used to retreive the Disability Insurance Policy Type information

### Description: This operation retrieves all Education Goals for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Education Goals including description and projected cost.

*Tags:* `EducationGoals`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Education Goals

### Description: The operation creates an Education Goal.<br /><br/>
>               Purpose: Allows for creation of Education Goals on a Fact Finder.

*Tags:* `EducationGoals`

### Description: This operation retrieves all Education Goal Expenses for the specified Education Goal ID.<br /><br/>
>               Purpose: Provides access to the Education Goal Expenses including description and annual cost.

*Tags:* `EducationGoals`

#### Input Parameters
* `educationGoalId` - _required_ - The ID of the Education Goal used to retrieve Education Goal Expenses

### Description: The operation creates an Education Goal Expense.<br /><br/>
>               Purpose: Allows for creation of Education Goal Expenses on a Fact Finder.

*Tags:* `EducationGoals`

#### Input Parameters
* `educationGoalId` - _required_ - The Education Goal ID used to locate the Goal to add the expense to

### Description: The operation removes an Education Goal Expense tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of an Education Goal Expense from a Fact Finder.

*Tags:* `EducationGoals`

#### Input Parameters
* `educationGoalId` - _required_ - The Education Goal ID used to locate the Goal to delete the Expense under
* `id` - _required_ - The Education Goal Expense ID used to identify which Education Goal Expense to remove

### Description: This operation retrieves a single Education Goal Expense for the specified Education Goal Expense ID.<br /><br/>
>               Purpose: Provides access to the Education Goal Expense including description and annual cost.

*Tags:* `EducationGoals`

#### Input Parameters
* `educationGoalId` - _required_ - The ID of the Education Goal used to retrieve Education Goal Expenses
* `id` - _required_ - The ID of the Education Goal Expense used to retreive the Education Goal Expense

### Description: The operation updates an Education Goal Expense.<br /><br/>
>               Purpose: Allows for complete replacement of an Education Goal Expense on a Fact Finder.

*Tags:* `EducationGoals`

#### Input Parameters
* `educationGoalId` - _required_ - The Education Goal ID used to locate the Goal to update the Expense under
* `id` - _required_ - The existing Education Goal Expense ID used to identify which Education Goal Expense to update

### Description: The operation removes an Education Goal tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of an Education Goal from a Fact Finder.

*Tags:* `EducationGoals`

#### Input Parameters
* `id` - _required_ - The Education Goal ID used to identify which Education Goal to remove

### Description: This operation retrieves a single Education Goal for the specified Education Goal ID.<br /><br/>
>               Purpose: Provides access to the Education Goal including description and projected cost.

*Tags:* `EducationGoals`

#### Input Parameters
* `id` - _required_ - The ID of the Education Goal used to retreive the Education Goal

### Description: The operation creates an Education Goal Expense.<br /><br/>
>               Purpose: Allows for creation of Education Goal Expenses on a Fact Finder.

*Tags:* `EducationGoals`

#### Input Parameters
* `id` - _required_ - The Education Goal ID used to locate the Goal to add the Expense to

### Description: This operation retrieves all Expense Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Expense Types including id and type description.

*Tags:* `ExpenseTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Expense Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves all Expense Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Expense Types including id and type description.

*Tags:* `ExpenseTypes`

#### Input Parameters
* `id` - _required_ - The ID of Expense Type used to retreive the Expense Type information

### Description: This operation retrieves all Expenses for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Expenses including description and Expense type.

*Tags:* `Expenses`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Expenses

### Description: The operation creates an Expense.<br /><br/>
>               Purpose: Allows for creation of Expenses on a Fact Finder.

*Tags:* `Expenses`

### Description: The operation removes an Expense tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of an Expense from a Fact Finder.

*Tags:* `Expenses`

#### Input Parameters
* `id` - _required_ - The Expense ID used to identify which Expense to remove

### Description: This operation retrieves a single Expense for the specified Expense ID.<br /><br/>
>               Purpose: Provides access to the Expense including description and Expense type.

*Tags:* `Expenses`

#### Input Parameters
* `id` - _required_ - The ID of the Expense used to retreive the Expense

### Description: The operation updates an Expense.<br /><br/>
>               Purpose: Allows for complete replacement of an Expense on a Fact Finder.

*Tags:* `Expenses`

#### Input Parameters
* `id` - _required_ - The existing Expense ID used to identify which Expense to update

### Description: The operation creates a Fact Finder.<br /><br/>
>               Purpose: Allows for creation of Fact Finders.

*Tags:* `FactFinders`

### Description: This operation retrieves all Fact Finder Modules for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Fact Finder Modules including description and policy type.

*Tags:* `FactFinderModules`

#### Input Parameters
* `factFinderId` - _required_ - The ID of the Fact Finder used to retrieve Fact Finder Modules

### Description: This operation retrieves a single Fact Finder Module for the specified Fact Finder Module ID.<br /><br/>
>               Purpose: Provides access to the Fact Finder Module including description and policy type.

*Tags:* `FactFinderModules`

#### Input Parameters
* `factFinderId` - _required_ - The ID of the Fact Finder used to retrieve Fact Finder Module
* `id` - _required_ - The ID of the Fact Finder Module used to retreive the Fact Finder Module

### Description: The operation updates a Fact Finder Module.<br /><br/>
>               Purpose: Allows for complete replacement of a Fact Finder Module on a Fact Finder.

*Tags:* `FactFinderModules`

#### Input Parameters
* `factFinderId` - _required_ - The ID of the Fact Finder used to identify the Fact Finder Module to update
* `id` - _required_ - The existing Fact Finder Module ID used to identify which Fact Finder Module to update

### Description: This operation retrieves a single Fact Finder for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Fact Finder including status.

*Tags:* `FactFinders`

#### Input Parameters
* `id` - _required_ - The ID of the Fact Finder used to retreive the Fact Finder

### Description: The operation updates a Fact Finder.<br /><br/>
>               Purpose: Allows for the updating of a Fact Finder.

*Tags:* `FactFinders`

#### Input Parameters
* `id` - _required_ - The existing Fact Finder ID used to identify which Fact Finder to update

### Description: The operation produces a Fact Finder based on input from a back office system.<br /><br/>
>               Purpose: Allows for advisors to compare the fact finder to the old plan prior to acceptance.

*Tags:* `FactFinders`

#### Input Parameters
* `id` - _required_ - The ID of the Fact Finder used to retreive the Fact Finder Snapshot

### Description: This operation retrieves all Filing Status Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Filing Status Types including id and type description.

*Tags:* `FilingStatusTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Filing Status Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves all Filing Status Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Filing Status Types including id and type description.

*Tags:* `FilingStatusTypes`

#### Input Parameters
* `id` - _required_ - The ID of Filing Status Type used to retreive the Filing Status Type information

### Description: This operation retrieves all Frequency Types for the specified country and entity.<br /><br/>
>               Purpose: Provides access to the Frequency Types including id and type description.

*Tags:* `FrequencyTypes`

#### Input Parameters
* `entity` - _required_ - The entity used to filter Frequency Types
    Possible values: CriticalIllnessInsurancePolicies, DisabilityInsurancePoliciesPremium, DisabilityInsurancePoliciesBenefit, Expenses, Liabilities, LifeInsurancePolicies, LongTermCareInsurancePoliciesBenefit, LongTermCareInsurancePoliciesPremium, RealEstateAssets, RetirementExpenses.
* `country` - _required_ - The country used to filter Frequency Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Frequency Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Frequency Types including id and type description.

*Tags:* `FrequencyTypes`

#### Input Parameters
* `id` - _required_ - The ID of Frequency Type used to retreive the Frequency Type information

### Description: This operation retrieves all Income Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Income Types including id and type description.

*Tags:* `IncomeTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Income Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Income Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Income Types including id and type description.

*Tags:* `IncomeTypes`

#### Input Parameters
* `id` - _required_ - The ID of Income Type used to retreive the Income Type information

### Description: This operation retrieves all Incomes for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Incomes including annual amount and start date.

*Tags:* `Incomes`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Incomes

### Description: The operation creates an Income.<br /><br/>
>               Purpose: Allows for creation of Incomes on a Fact Finder.

*Tags:* `Incomes`

### Description: The operation removes an Income tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of an Income from a Fact Finder.

*Tags:* `Incomes`

#### Input Parameters
* `id` - _required_ - The Income ID used to identify which Income to remove

### Description: This operation retrieves a single Income for the specified Income ID.<br /><br/>
>               Purpose: Provides access to the Income including annual amount and start date.

*Tags:* `Incomes`

#### Input Parameters
* `id` - _required_ - The ID of the Income used to retreive the Income

### Description: The operation updates an Income.<br /><br/>
>               Purpose: Allows for complete replacement of an Income on a Fact Finder.

*Tags:* `Incomes`

#### Input Parameters
* `id` - _required_ - The existing Income ID used to identify which Income to update

### Description: This operation retrieves all Liabilities for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Liabilities including owner and type.

*Tags:* `Liabilities`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Liabilities
* `externalSourceId` - _optional_ - The external source ID used to filter Liabilities

### Description: The operation creates a Liability.<br /><br/>
>               Purpose: Allows for creation of Liabilities on a Fact Finder.

*Tags:* `Liabilities`

### Description: The operation removes a Liability tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Liability from a Fact Finder.

*Tags:* `Liabilities`

#### Input Parameters
* `id` - _required_ - The Liability ID used to identify which Liability to remove

### Description: This operation retrieves a single Liability for the specified Liability ID.<br /><br/>
>               Purpose: Provides access to the Liability including owner and type.

*Tags:* `Liabilities`

#### Input Parameters
* `id` - _required_ - The ID of the Liability used to retreive the Liability

### Description: The operation updates a Liability.<br /><br/>
>               Purpose: Allows for complete replacement of a Liability on a Fact Finder.

*Tags:* `Liabilities`

#### Input Parameters
* `id` - _required_ - The existing Liability ID used to identify which Liability to update

### Description: This operation retrieves all Liability Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Liability Types including id and type description.

*Tags:* `LiabilityTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Liability Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Liability Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Liability Types including id and type description.

*Tags:* `LiabilityTypes`

#### Input Parameters
* `id` - _required_ - The ID of Liability Type used to retreive the Liability Type information

### Description: This operation retrieves all Life Insurance Policies for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Life Insurance Policies including description and policy type.

*Tags:* `LifeInsurancePolicies`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Life Insurance Policies

### Description: The operation creates a Life Insurance Policy.<br /><br/>
>               Purpose: Allows for creation of Life Insurance Policies on a Fact Finder.

*Tags:* `LifeInsurancePolicies`

### Description: The operation removes a Life Insurance Policy tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Life Insurance Policy from a Fact Finder.

*Tags:* `LifeInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The Life Insurance Policy ID used to identify which Life Insurance Policy to remove

### Description: This operation retrieves a single Life Insurance Policy for the specified Life Insurance Policy ID.<br /><br/>
>               Purpose: Provides access to the Life Insurance Policy including description and policy type.

*Tags:* `LifeInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The ID of the Life Insurance Policy used to retreive the Life Insurance Policy

### Description: The operation updates a Life Insurance Policy.<br /><br/>
>               Purpose: Allows for complete replacement of a Life Insurance Policy on a Fact Finder.

*Tags:* `LifeInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The existing Life Insurance Policy ID used to identify which Life Insurance Policy to update

### Description: This operation retrieves all Life Insurance Policy Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Life Insurance Policy Types including id and type description.

*Tags:* `LifeInsurancePolicyTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Life Insurance Policy Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Life Insurance Policy Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Life Insurance Policy Types including id and type description.

*Tags:* `LifeInsurancePolicyTypes`

#### Input Parameters
* `id` - _required_ - The ID of Life Insurance Policy Type used to retreive the Life Insurance Policy Type information

### Description: This operation retrieves all Lifestyle Asset Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Lifestyle Asset Types including id and type description.

*Tags:* `LifestyleAssetTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Lifestyle Asset Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Lifestyle Asset Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Lifestyle Asset Types including id and type description.

*Tags:* `LifestyleAssetTypes`

#### Input Parameters
* `id` - _required_ - The ID of Lifestyle Asset Type used to retreive the Lifestyle Asset Type information

### Description: This operation retrieves all Lifestyle Assets for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Lifestyle Assets including description and market value.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Lifestyle Assets

### Description: The operation creates a Lifestyle Asset.<br /><br/>
>               Purpose: Allows for creation of Lifestyle Assets on a Fact Finder.

*Tags:* `LifestyleAssets`

### Description: The operation removes a Lifestyle Asset tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Lifestyle Asset from a Fact Finder.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `id` - _required_ - The Lifestyle Asset ID used to identify which Lifestyle Asset to remove

### Description: This operation retrieves a single Lifestyle Asset for the specified Lifestyle Asset ID.<br /><br/>
>               Purpose: Provides access to the Lifestyle Asset including description and market value.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `id` - _required_ - The ID of the Lifestyle Asset used to retreive the Lifestyle Asset

### Description: The operation updates a Lifestyle Asset.<br /><br/>
>               Purpose: Allows for complete replacement of a Lifestyle Asset on a Fact Finder.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `id` - _required_ - The existing Lifestyle Asset ID used to identify which Lifestyle Asset to update

### Description: This operation retrieves all Long Term Care Insurance Policies for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Long Term Care Insurance Policies including description and premium.

*Tags:* `LongTermCareInsurancePolicies`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Long Term Care Insurance Policies

### Description: The operation creates a Long Term Care Insurance Policy.<br /><br/>
>               Purpose: Allows for creation of Long Term Care Insurance Policies on a Fact Finder.

*Tags:* `LongTermCareInsurancePolicies`

### Description: The operation removes a Long Term Care Insurance Policy tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Long Term Care Insurance Policy from a Fact Finder.

*Tags:* `LongTermCareInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The Long Term Care Insurance Policy ID used to identify which Long Term Care Insurance Policy to remove

### Description: This operation retrieves a single Long Term Care Insurance Policy for the specified Long Term Care Insurance Policy ID.<br /><br/>
>               Purpose: Provides access to the Long Term Care Insurance Policy including description and premium.

*Tags:* `LongTermCareInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The ID of the Long Term Care Insurance Policy used to retreive the Long Term Care Insurance Policy

### Description: The operation updates a Long Term Care Insurance Policy.<br /><br/>
>               Purpose: Allows for complete replacement of a Long Term Care Insurance Policy on a Fact Finder.

*Tags:* `LongTermCareInsurancePolicies`

#### Input Parameters
* `id` - _required_ - The existing Long Term Care Insurance Policy ID used to identify which Long Term Care Insurance Policy to update

### Description: This operation retrieves all Major Purchase Goal Types for the specified country.<br /><br/>
>               Purpose: Provides access to the Major Purchase Goal Types including id and type description.

*Tags:* `MajorPurchaseGoalTypes`

#### Input Parameters
* `country` - _required_ - The country used to filter Major Purchase Goal Types
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the Major Purchase Goal Type for the specified id.<br /><br/>
>               Purpose: Provides access to the Major Purchase Goal Types including id and type description.

*Tags:* `MajorPurchaseGoalTypes`

#### Input Parameters
* `id` - _required_ - The ID of Major Purchase Goal Type used to retreive the Major Purchase Goal Type information

### Description: This operation retrieves all Major Purchases for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Major Purchases including description and amount.

*Tags:* `MajorPurchaseGoals`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Major Purchases

### Description: The operation creates a Major Purchase.<br /><br/>
>               Purpose: Allows for creation of Major Purchases on a Fact Finder.

*Tags:* `MajorPurchaseGoals`

### Description: The operation removes a Major Purchase tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Major Purchase from a Fact Finder.

*Tags:* `MajorPurchaseGoals`

#### Input Parameters
* `id` - _required_ - The Major Purchase ID used to identify which Major Purchase to remove

### Description: This operation retrieves a single Major Purchase for the specified Major Purchase ID.<br /><br/>
>               Purpose: Provides access to the Major Purchase including description and amount.

*Tags:* `MajorPurchaseGoals`

#### Input Parameters
* `id` - _required_ - The ID of the Major Purchase used to retreive the Major Purchase

### Description: The operation updates a Major Purchase.<br /><br/>
>               Purpose: Allows for complete replacement of a Major Purchase on a Fact Finder.

*Tags:* `MajorPurchaseGoals`

#### Input Parameters
* `id` - _required_ - The existing Major Purchase ID used to identify which Major Purchase to update

### Description: This operation retrieves all Real Estate Assets for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Real Estate Assets including description and market value.

*Tags:* `RealEstateAssets`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Real Estate Assets

### Description: The operation creates a Real Estate Asset.<br /><br/>
>               Purpose: Allows for creation of Real Estate Assets on a Fact Finder.

*Tags:* `RealEstateAssets`

### Description: The operation removes a Real Estate Asset tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Real Estate Asset from a Fact Finder.

*Tags:* `RealEstateAssets`

#### Input Parameters
* `id` - _required_ - The Real Estate Asset ID used to identify which Real Estate Asset to remove

### Description: This operation retrieves a single Real Estate Asset for the specified Real Estate Asset ID.<br /><br/>
>               Purpose: Provides access to the Real Estate Asset including description and market value.

*Tags:* `RealEstateAssets`

#### Input Parameters
* `id` - _required_ - The ID of the Real Estate Asset used to retreive the Real Estate Asset

### Description: The operation updates a Real Estate Asset.<br /><br/>
>               Purpose: Allows for complete replacement of a Real Estate Asset on a Fact Finder.

*Tags:* `RealEstateAssets`

#### Input Parameters
* `id` - _required_ - The existing Real Estate Asset ID used to identify which Real Estate Asset to update

### Description: This operation retrieves all Retirement Goals for the specified Fact Finder ID.<br /><br/>
>               Purpose: Provides access to the Retirement Goals including retirement date.

*Tags:* `RetirementGoals`

#### Input Parameters
* `factFinderId` - _optional_ - The ID of the Fact Finder used to retrieve Retirement Goals

### Description: The operation creates a Retirement Goal.<br /><br/>
>               Purpose: Allows for creation of Retirement Goals on a Fact Finder.

*Tags:* `RetirementGoals`

### Description: The operation removes a Retirement Goal tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Retirement Goal from a Fact Finder.

*Tags:* `RetirementGoals`

#### Input Parameters
* `id` - _required_ - The Retirement Goal ID used to identify which Retirement Goal to remove

### Description: This operation retrieves a single Retirement Goal for the specified Retirement Goal ID.<br /><br/>
>               Purpose: Provides access to the Retirement Goal including retirement date.

*Tags:* `RetirementGoals`

#### Input Parameters
* `id` - _required_ - The ID of the Retirement Goal used to retreive the Retirement Goal

### Description: The operation updates a Retirement Goal.<br /><br/>
>               Purpose: Allows for complete replacement of a Retirement Goal on a Fact Finder.

*Tags:* `RetirementGoals`

#### Input Parameters
* `id` - _required_ - The existing Retirement Goal ID used to identify which Retirement Goal to update

### Description: This operation retrieves all Retirement Goal Expenses for the specified Retirement Goal ID.<br /><br/>
>               Purpose: Provides access to the Retirement Goal Expenses including description and amount.

*Tags:* `RetirementGoals`

#### Input Parameters
* `retirementGoalId` - _required_ - The ID of the Retirement Goal used to retrieve Retirement Goal Expenses

### Description: The operation creates a Retirement Goal Expense.<br /><br/>
>               Purpose: Allows for creation of Retirement Goal Expenses on a Fact Finder.

*Tags:* `RetirementGoals`

#### Input Parameters
* `retirementGoalId` - _required_ - The ID of the Retirement Goal to add the Retirement Goal Expense to

### Description: The operation removes a Retirement Goal Expense tied to a Fact Finder.<br /><br/>
>               Purpose: Allows for removal of a Retirement Goal Expense from a Fact Finder.

*Tags:* `RetirementGoals`

#### Input Parameters
* `retirementGoalId` - _required_ - The Retirement Goal ID used to locate the Goal to delete the Retirement Goal Expense under
* `id` - _required_ - The Retirement Goal Expense ID used to identify which Retirement Goal Expense to remove

### Description: This operation retrieves a single Retirement Goal Expense for the specified Retirement Goal Expense ID.<br /><br/>
>               Purpose: Provides access to the Retirement Goal Expense including description and amount.

*Tags:* `RetirementGoals`

#### Input Parameters
* `retirementGoalId` - _required_ - The ID of the Retirement Goal used to retrieve the Retirement Goal Expense
* `id` - _required_ - The ID of the Retirement Goal Expense used to retreive the Retirement Goal Expense

### Description: The operation updates a Retirement Goal Expense.<br /><br/>
>               Purpose: Allows for complete replacement of a Retirement Goal Expense on a Fact Finder.

*Tags:* `RetirementGoals`

#### Input Parameters
* `retirementGoalId` - _required_ - The Retirement Goal ID used to locate the Goal to update the Retirement Goal Expense under
* `id` - _required_ - The existing Retirement Goal Expense ID used to identify which Retirement Goal Expense to update

### Description: This operation retrieves information statistics for the current service.<br /><br/>
>               Purpose: Provides access to Service Information.

*Tags:* `FactFinderServiceInformation`

### Description: This operation retrieves all States and Provinces for the specified country.<br /><br/>
>               Purpose: Provides access to the States and Provinces.

*Tags:* `StatesProvinces`

#### Input Parameters
* `country` - _required_ - The country used to filter States and Provinces
    Possible values: UnitedStates, Canada.

### Description: This operation retrieves the States and Provinces for the specified id.<br /><br/>
>               Purpose: Provides access to the States and Provinces.

*Tags:* `StatesProvinces`

#### Input Parameters
* `id` - _required_ - The ID of the State or Province used to retreive the State or Province information

### Description: This operation retrieves a single Fact Finder User.<br /><br/>
>               Purpose: Provides access to a Fact Finder User information including the User ID.

*Tags:* `Users`

#### Input Parameters
* `username` - _required_ - The username used to look up the Fact Finder User information

### Description: The operation creates a Fact Finder User.<br /><br/>
>               Purpose: Allows for creation of Users to collect Fact Finder information.

*Tags:* `Users`

### Description: This operation retrieves all Fact Finders related to the specified Advisor's Clients.<br /><br/>
>               Purpose: Provides access to a Client Fact Finder listing.

*Tags:* `Users`

#### Input Parameters
* `advisorGuid` - _required_ - The Advisor Guid used to locate related Clients and then those Client's Fact Finders

### Description: This operation retrieves a list of Fact Finders related to the specified Advisor's Client.<br /><br/>
>               Purpose: Provides access to a Client's Fact Finders.

*Tags:* `Users`

#### Input Parameters
* `advisorGuid` - _required_ - The Advisor Guid used to locate related Clients
* `clientGuid` - _required_ - The Client Guid used to locate related Fact Finders

### Description: This operation retrieves a single Fact Finder User.<br /><br/>
>               Purpose: Provides access to a Fact Finder User information including the username.

*Tags:* `Users`

#### Input Parameters
* `id` - _required_ - The User ID used to look up the Fact Finder User information

### Description: This operation retrieves all Fact Finders for the specified username.<br /><br/>
>               Purpose: Provides access to the Fact Finder listing including status.

*Tags:* `Users`

#### Input Parameters
* `username` - _required_ - The username used to filter Fact Finders

## License

**flow**ground :- Telekom iPaaS / naviplancentral-com-factfinder-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
