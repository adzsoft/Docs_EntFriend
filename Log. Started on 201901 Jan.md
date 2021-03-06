

Call [@VikaAdl, @VladZamskoi]
    ###### Fri May 3 16:49:47 IDT 2019

Redesigned service page  
    [x] 1. Design cards as alternative to table-view for service page  
    ###### Tue Mar 26 21:18:34 IST 2019 init
    ###### Fri May 3 16:37:19 IDT 2019 done about 2 days ago

Considered fron-end framework to use: Vue.js  
    Based on insights from article:
        'React vs. Vue (vs. Angular)
        '  
            Fri May 3 16:07:34 IDT 2019  
            https://medium.com/fundbox-engineering/react-vs-vue-vs-angular-163f1ae7be56  

[] * Design: Main page of the service (after login)  
        ###### Sun Feb 17 19:46:29 EET 2019 init
        ###### Fri May 3 16:38:18 IDT 2019 done by this time

###### Thu May 2 2019  
    Shared v2 ServicePage UI screenshots with @AlexPerezChernov via Telegram  
    Feedback:  
        Alex:  
        > Hi, I don't remember whether you need to take 
            * persons assigned on a task. It has been omitted from the new version, 
            * and also there are no any menu / frequents actions at all. I mean it seems you need to go though yours main target activity (user stories), and ensure that everything is presented on UI

        Vlad Zamskoi. iOS & Android. Minsk & Tel-Aviv.
        > persons assigned on a task
        – no, they were not assignees in original mockup, they were more like collaborators. Now we have dedicated 4th column for that kind of activity
        > no any menu / frequents actions at all
        – It's temporary. Since we can't sync everyday (I'm too busy) fron-end developer asked to remove everything that's not needed to be implemented in the beginning. We're going to add a bit more of menus later.

###### Apr 11 2019 init
Met @AlexPerezChernov, got his feedback.

* Design: Landing page  
        ###### Sun Feb 17 19:46:29 EET 2019 init
        
        ###### Sun Feb 24 15:44:50 EET 2019
        Done partially. Delegated to @VladFid – designer  

        ###### Tue Mar 26 21:20:04 IST 2019
        "Testimonials" section left to be  

        ###### Tue Mar 26 22:18:13 IST 2019 done
        

7. LandingPage: Add Shevron-like arrow to "Начать Бесплатно" button  
    ###### Tue Mar 26 21:03:19 IST 2019
    reconsidering

    ###### Tue Mar 26 21:07:47 IST 2019
    we forgot what the task is about  


###### Tue Mar 26 20:34:45 IST 2019
1st regular sync call session  


3. 4 or more user stories  
    ###### Sun Feb 17 19:40:52 EET 2019
    Assigned to @VladZamskoi

    ###### Tue Mar 26 20:49:16 IST 2019
    Done on Fri, Mar 15th 2019


###### Sat Mar 2 13:10:42 IST 2019

1. ### Meeting (advisor feedback)
    ### Sat, Mar-2-2019, ?:TIME  
    assigned to @VikaAdler  
    assigned to @AlexPerez  
    @VladZamskoi is going to miss it (will be abroad)  

    @VikaAdl presented current progress to @AlexPerez. He hasn't yet approved start of coding.  

---

Yesterday night we had call and Skype work session: [@VikaAdl, @VladZamskoi, @vladFidrik].  

Main page list items categories.  

1. By type of human group
    1. Организация  
    2. Индивидуал  

2. By type of (role)  
    1. Банк
    2. Налоговая
    3. ФСЗН
    4. Клиент
    5. Подрадчик
    6. Коллега  


2. Idea description  
    Ru  
    We save about 1.5 hours per $4.99 monthly  

    ###### Sun Feb 24 15:48:16 EET 2019
    Done  

    Web приложение для индивидуальных предпринимателей (далее – ИП), которое помогает следить за денежными поступлениями на расчетные счета и вовремя отчитываться перед налоговой и ФСЗН.  

    Уникальность в том, что данное приложение – это персонализированный личный кабинет, объединяющий информацию о статусе обмена информацией с 3-мя различными службами – банком, налоговой и ФСЗН – с которыми необходимо сталкиваться любому ИП для того, чтобы удовлетворять требованиям законодательства к осуществлению коммерческой деятельности.  

    Каждая из этих служб предоставляет все больше и больше ПО для обмена данными между ней самой и ИП. Однако все они делают это независимо друг от друга – т. е. не предоставляют никаких программ, с помощью которых можно было бы осуществлять все необходимые административные процедуры, предусмотренные законодательством.  

    На сегодняшний день самому ИП приходится выяснять нюансы того, в какое время, в каких случаях и какие именно документы необходимо предоставлять в каждую из этих 3х служб. Это неудбно. И мы – те, кто это меняет.

    Features:  

    1. group documents sent to bank to the bundles to make it possible to re-send them all together each time when certain condition met.  
    
    E. g. each time I get money from certain customer, I am offered with 
    * one button to send all required reports to bank and  
    * simple form to order how much money to sent to my personal bank card and how much keep at corporate bank account  

    2. Based on what taxes plan I'm using, I can receive notifications (over mail as well as to mobile phone) about that it's time to submit the reports to my tax inspectors  

    3. Discover services I may need in order to grow and develop the business:  
    * other banks offers
    * 3-rd party services line accounting service, official consultations on taxes, social insurance etc.
  
    ###### Wed Feb 20 21:19:34 EET 2019
    ## HIGHEST priority 
    
    ###### Sun Feb 17 19:40:52 EET 2019
    Assigned to @VladZamskoi


4. Unit Economics + justification

    ###### Sun Feb 24 15:46:30 EET 2019
    @VikaAdler: Done  

    ###### Sun Feb 17 19:40:52 EET 2019  
    Assigned to @VikaAdler
  
    1. Costs_of_new_user_acquisition  
        1. Context Ad. Requests:  
        * Клиент банк для ИП беларусь  
        * Клиент банк для ИП россия  
        2. SMM  
        3. off-line PR  
  
    2. Life-time profit brought by one user  
        1. 2 month free period + monthly subscription  
            Hypothesis:  
            ```
            LifeTime == 3 months  
            && profitability_ratio_per_user = 1.5  
            => monthly subscription = 3 * Costs_of_new_user_acquisition * profitability_ratio_per_user  
            ```
    
        2. (for future) partners deals. The value we have: we know about what kind of expenses business user makes in order to do their business). I. e. we can provide the target ad for these users. 

    ###### Mon Feb 18 13:09:29 MSK 2019  
    Calculating the unit economics
    https://docs.google.com/document/d/1vafNY93s2h_FyFRLvyoUfwUBjf-ZRVmoS9ZjKEgXYW8/edit

    ###### Wed Feb 20 19:14:39 EET 2019
    $4.99 – desired maximum monthly subscription  


###### Sat Feb 23 17:40:30 EET 2019
## About Company  
EntFriend™ – сервис, разрабатываемый частной компанией vika&&vlad™.  Проект был основан 10-мя программистами и одним предпринимателем в рамках образовательного проекта в начале 2019-го года и продолжил свое существование в след за тем, как его основатели затруднились представить жизнь друг без друга.  

EntFriend™ – сокращение от английского “Enterpreneur’s Friend”, что переводится, как “друг предпринимателя”. Произносится это, как  “энт-фрэнт”.  

Основной принцип, которого придерживаются все, с кем мы сотрудничаем и вместе разрабатываем EntFriend™ – становись богаче, помогая другим.  


1. Pick color scheme  
    * https://coolors.co/794fd8-56e39f-ef6f6c-d9f0ff-ffffff 
        || https://coolors.co/794fd8-56e39f-ef9c6c-d9f0ff-ffffff  

    ###### Sun Feb 17 21:32:20 EET 2019
    Assigned to @VikaAdler  

    ###### Sun Feb 24 15:45:39 EET 2019
    Cancelled. We're doing it on the fly.  


###### Sun Feb 24 15:41:56 EET 2019
About 4h more spent in skype with designer: [@VladZamskoi, @VikaAdler, @VladFid]  
Completed:  
    * Landing page design draft. It's been reworked about 2 times already during yesterday  
    * Login page draft  


###### Sat Feb 23 17:04:14 EET 2019
4h 20m talk in skype [@VladZamskoi, @VikaAdler]  


###### Wed Feb 20 21:15:21 EET 2019
At around 7pm  
10m Call: [@VladZamskoi, @VikaAdler]  
Vika is quite aggressive. VladZamskoi is relaxed but I haven't done anything yet. That's why Vika is quite aggressive actually.  


###### Sun Feb 17 20:01:05 EET 2019
### 2h 10m Call: [@VladZamskoi, @VikaAdler]  

1. Todo is defined, tasks assigned  

2. New name  
EntFriend

3. Ad slogan:  
    You EntFriend – the best team ever!  

4. scheduled Next call: [@VladZamskoi, VikaAdler]: Wed, Feb-20-2019, 6:30pm  

5. Agreed on milestone: Sat, Mar-2-2019  
  apply to @AlexPerez. @VladZamskoi is going to miss it (will be abroad)  


###### Before Sun Feb 17 20:01:05 EET 2019

Mission
Help small and middle-sized business chiefs to manage their money. With or without accountant.  


Project started on Mon, Jan, 28th, 2019 in BSU.

Team:  
* Alex Perez Chernov
* Viktoria Adler
* Vlad Zamskoi
* Artem 
