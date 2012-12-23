# Ruby on Rails Tutorial: sample application

This is the sample application for
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).



4.6.a.
s.split('').shuffle.join

4.6.b.


class String
  def shuffle
    self.split('').shuffle.join
  end
end
=> nil
>> "foobar".shuffle


4.6.c.
person1 = { :first => "john", :last => "doe" } 
person2 = { :first => "jane", :last => "doe" }
person3 = { :first => "child", :last => "doe" }
params = { :father => person1, :mother => person2, :child => person3 }
params[:father][:first]


4.6.d.
http://www.ruby-doc.org/core-1.9.3/Hash.html
