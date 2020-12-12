import amino
import random
from apscheduler.schedulers.blocking import BlockingScheduler
def job1():
    client = amino.Client()
    client.login(email='damdel344@gmail.com',password='CFCFQKFKRF344')
    sub_client = amino.SubClient(comId='156542274',profile=client.profile)
    sub_client.send_message(message="!bc", chatId="41fab383-550b-0e75-1ee9-0e4f605762f7")
    sub_client.send_message(message="!capital 5000", chatId="41fab383-550b-0e75-1ee9-0e4f605762f7")
    client.logout()
scheduler = BlockingScheduler()
scheduler.add_job(job1, 'interval', hours=1.004)
scheduler.start()
