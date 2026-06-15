class Solution {
public:
    ListNode* mergeTwoLists(ListNode* list1, ListNode* list2) {
        if (!list1) return list2;
        if (!list2) return list1;
        if (list1->val
        } else {
            list2->next = mergeTwoLists(list1, list2->next);
            return list2;
      
