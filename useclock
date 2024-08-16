import time

def pomodoro_timer(work_time=25, break_time=5):
    print("开始专注时钟")
    while True:
        print("工作时间：", work_time, "分钟")
        for i in range(work_time * 60):
            time.sleep(1)
            print("\r剩余时间：{:02d}:{:02d}".format(work_time - i // 60, i % 60), end="")
        print("\n休息时间：", break_time, "分钟")
        for i in range(break_time * 60):
            time.sleep(1)
            print("\r剩余时间：{:02d}:{:02d}".format(break_time - i // 60, i % 60), end="")
        print("\n")

if __name__ == "__main__":
    pomodoro_timer()
