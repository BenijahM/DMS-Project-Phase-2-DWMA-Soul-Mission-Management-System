# DMS Project Phase 2: DWMA Soul Mission Management System Software Testing
Be'Nijah Mitchell 
Project from course: CEN 3024-13038 – Software Development 1

This program demonstrates the use of object-oriented programming, input validation, file importing, record management, and data processing in Java. The DWMA Soul Mission Management System allows users to manage soul mission records and calculate Death Scythe qualification progress. PHASE 2: UNIT TESTING

Code Updates:

    - Output Readability: Formatted the records to display in columns for better readability.
    - String inputs updates: Changed string inputs from full words to letters.
        - True/False = Enter t/f (not case sensitive)
        - Yes/No = Enter y/n (not case sensitive)
    - Partner Type fields: Changed partner type field entries from strings to int.
        - Choices: 1.Team, 2.Meister, 3.Weapon
        - Enter: Choice 1-3
    - Txt File Updates:
        - records.txt (ENTER for option 2 on Menu)
        - testRecords.txt (used in the FileImporter test)

Testing Units:

    - RecordManagerTest:
        - Add Record Test
            - Negative Test: Add Duplicate record
          - Remove Record Test
              - Negative Test: Remove Nonexistent record
          - Update Record Test
              - Negative Test: Update Nonexistent record
          - Display All Records Test
              
    - ProgressCalculatorTest:
        - Calculate Qualification Progress Test
            - Negative Test: Qualification Progress
            
    - FileImporterTest:
        - Import Records Test
            - Negative Test: File Import (Throws the error)




