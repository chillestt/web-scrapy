# conda activate crawl

# scrapy init 

# spider folder 
create class with: allowed domain, start domain...
then code to crawl 
    + scrapy shell
    + fetch
    + scrapy crawl bookspider(filename or classname) -o bookspider.csv

# file items.py 
    chua class item
# pipeline 
    chua cac class pipeline de xu ly du leisure
# file settings.py 
-> co PIPELINEs 
-> chua cac pipeline se duoc thuc thi, co do uu tien, so cang nho thi do uu tien cang cao 

# connect to mysql
    -self.conn = self.connector.connect(host, user, password, database)
    self.cur = self.conn.cursor()
    self.cur.execute(cau len sql)


