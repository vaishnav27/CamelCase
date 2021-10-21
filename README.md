# CamelCase

int camelcase(string s) {
    int count=1;
    for (int i=0; i<s.length(); i++) {
        if (isupper(s.at(i))) {
           count++;
        }
    }
    return count;
}
