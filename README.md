public class RandomContactFactory {

    Public static list<Contact> generateRandomContacts(integer,numofContacts,string,LastNameGen){
        List <Contact> con = new list <Contact>();
        for (integer i=0 ; i<numofContacts; i++ ){
            contact a = new contact(FirstName = LastNameGen, LastName=LastNameGen);
            con.add(a);
            
        }
        return con; 
    }
}
