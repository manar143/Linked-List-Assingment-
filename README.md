int main()
{
    Node*head=NULL;
    Node*second=NULL;
    Node*third=NULL;
    Node*fourth=NULL;
    Node*fifth=NULL;
    



    head=new Node();
    second=new Node();
    third=new Node();
    fourth=new Node();
    fifth=new Node();
    sixth=new Node();

    
    
    
    
    
    head->data='m';
    head->next=second;
    second->data='a';
    second->next=third;
    third->data='n';
    third->next=fourth;
    fourth->data='a';
    fourth->next=fifth;
    fifth->data='r';
    fifth->next=NULL;

   

    
    
 cout<< printList(head);
    
    return 0;
}
