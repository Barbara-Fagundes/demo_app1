class Micropost < ActiveRecord::Base
#  attr_accessible :content, :user_id

  belongs_to :user

  validates :content, :length => { :maximum => 140 }
end



#c Microposttroy
 #   @user.destroy
 #       respond_to do |format|
#		      format.html { redirect_to users_url, notice: 'User was successfully destroyed.' }
#		            format.json { head :no_content }ApplicationRecord
#end
