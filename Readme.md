## Hi there!

# This project is my first calculator project that I wrote on Motoko Playground code IDE. I used the Motoko language effectively in this project. You can find the details from the link below!

[Motoko Playground](https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/?tag=1579402164)

## My code is below

// my-first-calculator-motoko-playground

actor calculator {

var hucre: Int = 0;

    public func sum(s : Int) : async Int  {
      hucre += s;
      hucre

};

    public func sub(s : Int) : async Int  {
      hucre -= s;
      hucre

};

    public func multiply(s : Int) : async Int  {
      hucre += s;
      hucre

};

    public func divide(s : Int) : async ?Int  {
    if  (s == 0) {
      null
    }
    else {
        hucre /= s;
        ?hucre
    }

};
public func clear(): async () {
hucre := 0;
}
};
