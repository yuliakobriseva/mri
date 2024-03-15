# mri
class MRI:
    def __init__(self, patient_name, scan_type, scan_duration_minutes):
        self.patient_name = patient_name
        self.scan_type = scan_type
        self.scan_duration_minutes = scan_duration_minutes

    def start_scan(self):
        print(f"Starting {self.scan_type} MRI scan for patient {self.patient_name}...")
        print(f"Scan duration: {self.scan_duration_minutes} minutes")
        # Simulating the scan process
        print("Scanning...")

    def analyze_results(self):
        print(f"Analyzing results of {self.scan_type} MRI scan for patient {self.patient_name}...")
        # Simulating result analysis process
        print("Analyzing MRI images...")
        print("Generating report...")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the MRI class
    mri_scan = MRI(patient_name="John Doe", scan_type="Brain", scan_duration_minutes=30)

    # Starting the MRI scan
    mri_scan.start_scan()

    # Analyzing the MRI results
    mri_scan.analyze_results()
