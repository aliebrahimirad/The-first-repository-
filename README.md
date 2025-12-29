from datetime import datetime

def run_task(task_name first):
    now = datetime.now().strftime("%Y-%m-%d %H:%M:%")
    print(f"✅ Task '{task_name}' executed successfully.")
    print(f"🕒 Time: {now}")

if __name__ == "__main__":
    run_task("Sample GitHub Task")

