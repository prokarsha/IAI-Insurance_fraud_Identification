# EDA_on_Insurance_fraud_Identification #
This dataset seems to contain information about insurance claims related to automobile accidents. Here's a breakdown of the columns:

    Month: Month of the accident.
    WeekOfMonth: Week number within the month.
    DayOfWeek: Day of the week of the accident.
    Make: Make of the vehicle involved in the accident.
    AccidentArea: Whether the accident occurred in an urban or rural area.
    DayOfWeekClaimed: Day of the week the claim was made.
    MonthClaimed: Month the claim was made.
    WeekOfMonthClaimed: Week number within the month the claim was made.
    Sex: Gender of the policyholder.
    MaritalStatus: Marital status of the policyholder.
    Age: Age of the policyholder.
    Fault: Who was at fault in the accident.
    PolicyType: Type of insurance policy.
    VehicleCategory: Category of the vehicle.
    VehiclePrice: Price range of the vehicle.
    FraudFound_P: Whether fraud was found in the claim (binary: 0 for no, 1 for yes).
    PolicyNumber: Policy number.
    RepNumber: Representative number.
    Deductible: Deductible amount.
    DriverRating: Driver rating.
    Days_Policy_Accident: Number of days since the policy was taken out until the accident.
    Days_Policy_Claim: Number of days since the policy was taken out until the claim was made.
    PastNumberOfClaims: Number of past claims.
    AgeOfVehicle: Age of the vehicle.
    AgeOfPolicyHolder: Age group of the policyholder.
    PoliceReportFiled: Whether a police report was filed for the accident.
    WitnessPresent: Whether a witness was present.
    AgentType: Type of insurance agent.
    NumberOfSuppliments: Number of supplementary policies.
    AddressChange_Claim: Whether there was a change of address in conjunction with the claim.
    NumberOfCars: Number of cars.
    Year: Year of the incident.
    BasePolicy: Base policy type.
    ClaimSize: Size of the claim.

Each row in the dataset represents a different insurance claim

This report explores machine learning models for insurance fraud prediction, emphasizing data cleaning, pre-processing, and model evaluation. Logistic Regression demonstrates high accuracy but low precision and recall, indicating potential false positives and missed fraud cases. Decision Tree presents balanced performance with slightly lower accuracy, while Random Forest achieves the highest accuracy but struggles with recall. These findings underscore the importance of model selection and highlight areas for enhancing fraud detection in insurance claim processing systems.
